# Colorfilter
a simple colorfilter script with menu for Arma 2

Installation:

in your init.sqf put the following:

	if (!isDedicated) then {
		// Color Filter Settings
		[false] execVM "addons\colorsettings.sqf";
	};

in your click_actions~>config.sqf add the following:

	["NVGoggles",			"Apply Color Filter",				"if (dialog) then {closeDialog 0;};[true] execVM 'addons\colorsettings.sqf';","true"]


thats it... hf
