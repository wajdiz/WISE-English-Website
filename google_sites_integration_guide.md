# Google Sites Integration Guide

This document provides instructions for integrating the Online Toxicity Education interactive content into Google Sites.

## Method 1: Embedding HTML Files Directly

Google Sites allows you to embed HTML content using the Embed feature. Here's how to integrate our HTML files:

1. **Log in to Google Sites** and open your site for editing.

2. **Add an Embed element**:
   - Click the "Insert" button in the right sidebar
   - Select "Embed" from the dropdown menu
   - Choose "Embed code"

3. **Insert the HTML code**:
   - Open the HTML file you want to embed (e.g., index.html or any scenario page)
   - Copy the entire HTML code from the file
   - Paste it into the embed code field in Google Sites
   - Click "Next" and then "Insert"

4. **Adjust the size and position** of the embedded content as needed.

5. **Repeat for each page** you want to include in your Google Site.

## Method 2: Using iframes (Recommended)

For better control and separation of content, you can use iframes to embed the HTML files:

1. **Create a new page** in Google Sites for each section or scenario.

2. **Add an Embed element** as described above.

3. **Insert an iframe code** that references the HTML file:
   ```html
   <iframe src="https://wblbnhsf.manus.space/index.html" width="100%" height="600px" frameborder="0"></iframe>
   ```

4. **Customize the iframe** by adjusting:
   - The `src` attribute to point to the specific page you want to embed
   - The `width` and `height` attributes to fit your Google Site layout
   - Add `scrolling="yes"` if the content requires scrolling

5. **Example for embedding a specific scenario page**:
   ```html
   <iframe src="https://wblbnhsf.manus.space/interactive_prototypes/scenario_cyberbullying.html" width="100%" height="700px" frameborder="0" scrolling="yes"></iframe>
   ```

## Organizing Content in Google Sites

Here's a suggested structure for organizing the content in Google Sites:

1. **Home Page**: Embed the main index.html to provide an overview and navigation.

2. **Interactive Tools Section**: Create a page that focuses on the three main interactive tools:
   - Toxicity Type Explorer
   - Response Strategy Decision Tree
   - Safety Settings Simulator

3. **General Scenarios Section**: Create a page or subpages for the original scenario pages.

4. **Qatar and GCC Scenarios Section**: Create a dedicated page or subpages for the culturally relevant scenarios.

## Troubleshooting

- If embedded content appears too small, increase the iframe height and width.
- If styling looks different in Google Sites, you may need to adjust the CSS in the HTML files.
- If interactive elements don't work, ensure JavaScript is enabled in your browser.

## Additional Resources

- [Google Sites Help: Add HTML, CSS & JavaScript](https://support.google.com/sites/answer/7761466)
- [Google Sites Help: Embed content on your site](https://support.google.com/sites/answer/90569)

## Contact for Support

If you encounter any issues with the integration, please reach out for assistance.
