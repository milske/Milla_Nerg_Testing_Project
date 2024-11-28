## Summary (Summarize the bug encountered concisely)

In the Gitlab in Create New Project page, there is a typo in one of the four buttons to create a new project. Instead of "Create blank project", it says "Create black project".

## Steps to reproduce

1.  Login to Gitlab account
2.  Navigate to the Project Creation Page https://gitlab.com/projects/new
3.  See the button Create Blank Project.

## What is the current bug behavior?

The text reads incorrectly Create "black" project.

## What is the expected correct behavior?

The text should say Create "blank" project to describe correctly the function of the link.

## Relevant logs and/or screenshots

Template\Image\Bug_Project_create_blank.png

<!--- Code from the console where the bug would be:
<a href="#blank_project" data-testid="panel-link" data-qa-panel-name="blank_project" class="new-namespace-panel gl-flex gl-w-full gl-shrink-0 gl-flex-col gl-items-center gl-rounded-base gl-border-1 gl-border-solid gl-border-gray-100 gl-px-3 gl-py-6 hover:!gl-no-underline lg:gl-flex-row"><div class="new-namespace-panel-illustration gl-flex gl-shrink-0 gl-justify-center"><img aria-hidden="" src="/assets/webpack/project-create-new-sm.d02514e7.svg"></div> <div class="gl-pl-4"><h3 class="gl-text-size-h2 gl-text-inherit">
Create blank project
</h3> <p class="gl-text-gray-900">
Create a blank project to store your files, plan your work, and collaborate on code, among other things.
 </p></div></a> -->

## Possible fixes

Fix the code: Update the text string to "blank"
Make sure the text is updated, and see if the same bug appears anywhere else in the website. If so, correct them also.

<!--- Code from the console where the bug would be:
<a href="#blank_project" data-testid="panel-link" data-qa-panel-name="blank_project" class="new-namespace-panel gl-flex gl-w-full gl-shrink-0 gl-flex-col gl-items-center gl-rounded-base gl-border-1 gl-border-solid gl-border-gray-100 gl-px-3 gl-py-6 hover:!gl-no-underline lg:gl-flex-row"><div class="new-namespace-panel-illustration gl-flex gl-shrink-0 gl-justify-center"><img aria-hidden="" src="/assets/webpack/project-create-new-sm.d02514e7.svg"></div> <div class="gl-pl-4"><h3 class="gl-text-size-h2 gl-text-inherit">
Create blank project
</h3> <p class="gl-text-gray-900">
Create a blank project to store your files, plan your work, and collaborate on code, among other things.
 </p></div></a> -->

## Whom do you report/ Assign To/ Tags

    /label ~bug ~reproduced ~trivial ~typo ~UI ~projectpage
    /cc @project-manager
    /assign @developer, @UI-team

## Priority

Trivial.

This is not a critical issue and does not affect the functionality of the website. It is a bug in the UI, the users can still use the project button and albeit the misspelling, the users can most likely still understand the usage of the button. Would be nice to have it fixed when possible though.
