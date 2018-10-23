# Project 7 - WordPress Pentesting

Time spent: **4** hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. (Required) WordPress	<=	4.2.3	- Nav	Menu	Title	Cross-Site	Scripting	(XSS)
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version: 4.2.4
  - [ ] GIF Walkthrough: ![Accesibility Attack](https://github.com/dolojimz/Security_Shepard/blob/master/AccessibilityAttck.gif)
    - [ ] Steps to recreate: Insert Javascript code into Font Settings titles in Accesbility Options
    
1. (Required) WordPress	3.3-4.7.4	- Large	File	Upload	Error	XSS
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version: 4.2.15 
  - [ ] GIF Walkthrough: 
  ![Large File Attack](https://github.com/dolojimz/Security_Shepard/blob/master/LargeFileAttack.gif)
    - [ ] Steps to recreate: Add javascript code into photo that is too large to upload and attempt to upload the image

1. (Required) WordPress	<=	4.2.3	- Widgets	Title	Cross-Site	Scripting	(XSS)
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version: 4.2.4
  - [ ] GIF Walkthrough: ![Widget Attack](https://github.com/dolojimz/Security_Shepard/blob/master/widgetAttck.gif)
    - [ ] Steps to recreate: Add javascript code into text widget 

1. (Optional) WordPress	<=	4.3	- Authenticated	Shortcode	Tags	Cross-Site	Scripting	(XSS)
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version: 4.2.5
  - [ ] GIF Walkthrough: ![Short Code Attack](https://github.com/dolojimz/Security_Shepard/blob/master/xssVulnAttack.gif)
    - [ ] Steps to recreate: Add javascript code to body of a new page 

## Assets

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

## License

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
