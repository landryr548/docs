{{Page_Title}}
{{Flags
|State=Ready to Use
|Editorial notes=
|Checked_Out=No
}}
{{Standardization_Status|W3C Editor's Draft}}
{{API_Name}}
{{Summary_Section|The tab-size CSS property is used to customise the width of a tab (U+0009) character.}}
{{CSS Property
|Initial value=8
|Applies to=block containers
|Inherited=Yes
|Media=visual
|Computed value=the specified integer or an absolute length
|Animatable=No
|CSS object model property=
|CSS percentages=
|Values={{CSS Property Value
|Data Type=<integer>
|Description=The number of spaces in a tab. Must be positive.
}}{{CSS Property Value
|Data Type=inherit
|Description=Inherits from the parent element.
}}
}}
{{Examples_Section
|Not_required=No
|Examples={{Single Example
|Language=CSS
|Description=Example of using different tab-size.
|Code=/**
Examples of using the tab-size prop
*/

.tab--size4 {
	tab-size: 4;
}

.tab--size8 {
	tab-size: 8;
}

.tab--size12 {
	tab-size: 12;
}

.tab--size0 {
	tab-size: 0;
}
|LiveURL=http://code.webplatform.org/gist/5673098
}}
}}
{{Notes_Section
|Usage=
|Notes=The tab character (unicode U+0009) is converted to space characters (unicode U+0020) by the white space rule (default is normal) which collapses multiple white space characters. Therefor this rule only makes sense inside a parent that cancels the white-space rule. For example the pre tag (which does this by default, setting it to pre-wrap) . See the example.
|Import_Notes=
}}
{{Related_Specifications_Section
|Specifications={{Related Specification
|Name=CSS Text Module Level 3
|URL=http://dev.w3.org/csswg/css-text/
|Status=Editor's draft
|Relevant_changes=
}}
}}
{{See_Also_Section
|Manual_links=
|External_links=
|Manual_sections=
}}
{{Topics|CSS}}
{{External_Attribution
|Is_CC-BY-SA=No
|Sources=MDN
|MDN_link=https://developer.mozilla.org/en-US/docs/Web/CSS/tab-size
|MSDN_link=
|HTML5Rocks_link=
}}
{{Compatibility_Section
|Not_required=No
|Imported_tables=
|Desktop_rows=
|Mobile_rows=
|Notes_rows=
}}