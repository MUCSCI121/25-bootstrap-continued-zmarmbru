# Lecture 24 Practice
In this practice we are going to create a webpage with a Bootstrap Navbar that automatically transitions from desktop layout to mobil layout.  It will also have a form which utilizes the Bootstrap Grid to layout the form elements.  The Bootstrap Form elements will include validation messages and when the user clicks the submit button a modal will appear if the form is valid.

![image](.assets/lecture24Demo.gif)

## Notes
* The the links in the Navbar should go to the appropriate Bootstrap, W3Schools, and Mozilla Developer Network pages.
* Form validation requires JavaScript code added to perform the validation.  It is located below the example form on the Validation page.

## References
* [Quick Start](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
* [Navbar](https://getbootstrap.com/docs/5.3/components/navbar/)
* [Grid](https://getbootstrap.com/docs/5.3/layout/grid/)
* [Form](https://getbootstrap.com/docs/5.3/forms/overview/)
* [Spacing](https://getbootstrap.com/docs/5.3/utilities/spacing/)
* [Modal](https://getbootstrap.com/docs/5.3/components/modal/)
----

## Configuration

### GitDoc

GitDoc is a great extension to automatically commit and push changes into the repository. For developers who are just getting started with web development, configuring this extension to automatically save their changes can make the introduction into git version control a much less intimidating experience. Because the extension cannot be configured by default to automatically push the changes up to the repository, users will need to update the settings the first time they launch project in Codespaces.

1. On the right-hand side of the `Codespaces` editor, click on the `Extensions` icon.

![image](.assets/extensionIcon.jpg) 

2. Once the `Extensions` sidebar expands, click on the gear icon in the `GitDoc` extension card and then select `Extension Settings` from the menu.

![image](.assets/extensionSettingClick.jpg)

3. Update the `Auto Commit Delay` to the number of milliseconds you would like the plugin wait before checking for file changes. The number is in milliseconds, 1 second = 1000 milliseconds. I've found the 5000 is a good number to use.

![image](.assets/autoCommitDelay.jpg) 

4. (Optional) Change the `Commit Validation Level` to `none`. This will allow all changes, even those that might include code which has errors in it, to be saved.

![image](.assets/commitValidation.jpg) 

5. Check the box associated with `Enabled` under the `Commit Validation Level` section.

6. Refresh the page in your browser so that the settings can be applied to the editor.
