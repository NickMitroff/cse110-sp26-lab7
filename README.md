Nick Mitroff

1. We want to use GitHub Actions to run our tests whenever code is pushed. That way, anyone can use the test pipeline just by pushing code, without having to know how to run it locally.
2. No - Ideally, our functions are pretty short, so end-to-end testing would be overkill for checking the return value of one function.
3. Navigation mode analyzes a single page load, which is useful for generating performance metrics in Lighthouse. However, navigation mode cannot analyze our interactions with the page such as form submissions. Snapshot mode doesn't analyze the load and doesn't measure performance, but it can track our interactions with the page.
4. In Performance, our website can load faster when doing back/forward navigations if we create a back/forward cache. In Acceessibility, the website should set the "lang" attribute, so that screen readers correctly determine that the website is in English and not the user's default language. In SEO, the website should have a meta description for better appearance in search results.





