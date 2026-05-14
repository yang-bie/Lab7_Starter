Yang Bie
1. I would fit my automated tests within a GitHub Action that runs whenever code is pushed.
   This is the best place because the test will be run automatically every time new code is added to the repo. It helps catch bugs early and makes sure the project still works after changes are made. Compared with only running tests manually, GitHub Action is more reliable because developers might forget to run tests before pushing. This also helps prevent borken code from being added to the project.
2. No. 
   End-to-end tests are manily used to test the whole user flow. If I only want to check whether one function returns the correct output, I should use a unit test instead.
3. Navigation mode analyzes the page from the beginning of a page load. It measures loading performance, such as First Contentful Paint, Largest Contentful Paint, Total 
   Blocking Time, Cumulative Layout Shift, and Speed Index. This is useful when we want to know how well the site performs when a user first opens it. 
   Snapshot mode analyzes the current state of the page at one specific moment. It does not focus on the full page-loading process. Instead, it checks the page as it currently exists, which is useful after interacting with the site or when checking accessibility, best practices, and SEO for the current page state.
4. 
        *Add a `lang` attribute to the `<html>` element, such as `<html lang="en">`, to improve accessibility and localization.
        *Add a meta description, such as `<meta name="description" content="...">`, so search engines can better understand the page content.
        *Improve JavaScript performance by minifying JavaScript and reducing unused JavaScript. The Lighthouse navigation result showed possible savings from both minifying JavaScript and reducing unused JavaScript.




