#CONFIGURATION = Debug
CONFIGURATION = Release

all:
	mkdir -p build/Release
	$(MAKE) -C ../../lib/xml_compiler
	xcodebuild -alltargets -configuration $(CONFIGURATION) build

clean:
	rm -rf build
	rm -f Info.plist
	rm -f *.xcodeproj/*.mode1
	rm -f *.xcodeproj/*.mode1v3
	rm -f *.xcodeproj/*.pbxuser
	rm -rf *.xcodeproj/xcuserdata
	rm -rf *.xcodeproj/project.xcworkspace/xcuserdata
	make -C ../../lib/xml_compiler clean

xcode:
	open *.xcodeproj

dump_data:
	@./build/Release/dump_xml_compiler_result \
	/Applications/KeyRemap4MacBook.app/Contents/Resources \
	/Applications/KeyRemap4MacBook.app/Contents/Resources \
	dump_data

dump_tree:
	@./build/Release/dump_xml_compiler_result \
	/Applications/KeyRemap4MacBook.app/Contents/Resources \
	/Applications/KeyRemap4MacBook.app/Contents/Resources \
	dump_tree

dump_number:
	@./build/Release/dump_xml_compiler_result \
	/Applications/KeyRemap4MacBook.app/Contents/Resources \
	/Applications/KeyRemap4MacBook.app/Contents/Resources \
	dump_number

dump_identifier_except_essential:
	@./build/Release/dump_xml_compiler_result \
	/Applications/KeyRemap4MacBook.app/Contents/Resources \
	/Applications/KeyRemap4MacBook.app/Contents/Resources \
	dump_identifier_except_essential

dump_symbol_map:
	@./build/Release/dump_xml_compiler_result \
	/Applications/KeyRemap4MacBook.app/Contents/Resources \
	/Applications/KeyRemap4MacBook.app/Contents/Resources \
	dump_symbol_map

output_bridge_essential_configuration_enum_h:
	@./build/Release/dump_xml_compiler_result \
	/Applications/KeyRemap4MacBook.app/Contents/Resources \
	/Applications/KeyRemap4MacBook.app/Contents/Resources \
	output_bridge_essential_configuration_enum_h

output_bridge_essential_configuration_default_values_c:
	@./build/Release/dump_xml_compiler_result \
	/Applications/KeyRemap4MacBook.app/Contents/Resources \
	/Applications/KeyRemap4MacBook.app/Contents/Resources \
	output_bridge_essential_configuration_default_values_c

output_bridge_essential_configuration_identifiers_m:
	@./build/Release/dump_xml_compiler_result \
	/Applications/KeyRemap4MacBook.app/Contents/Resources \
	/Applications/KeyRemap4MacBook.app/Contents/Resources \
	output_bridge_essential_configuration_identifiers_m
