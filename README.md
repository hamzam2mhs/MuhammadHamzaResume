# Hosting and Formatting a Resume Using Markdown and Jekyll

This README describes the practical steps of how to host and format a resume using the software stack used for this assignment: Markdown and Jekyll. It also relates these steps to the general principles of current Technical Writing, as explained in Andrew Etter's book Modern Technical Writing.

## Prerequisites
- We need to learn markdown. The easiest way to do it is to use [markdown pad](http://www.markdownpad.com/) which is suggested by Andrew Etter.
- We need a resume and it should be formatted in Markdown language.

## Practical Steps

1. **Create a GitHub Account**: Create a GitHub account if you don't already have one.


2. **Create a Repository**: Create a new repository on GitHub and name it after your username.

3. **Download a Markdown Editor**: Download and install a Markdown editor, such as Typora or VS Code with the Markdown Extension. This editor enables you to create and edit Markdown files easily.

4. **Create a Resume in Markdown**: Create a new file in your repository and name it "resume.md". Use Markdown syntax to format your resume, including headings, lists, and tables. Include all relevant information, such as your contact information, work experience, education, skills, and projects.

5. **Create a Jekyll Site**: Use Jekyll to create a new website. You can either follow the Jekyll [documentation](https://jekyllrb.com/docs/) or use a [Jekyll theme.](https://jekyllthemes.io/github-pages-themes) Jekyll is a static site generator that allows you to convert your Markdown files into HTML pages.

6. **Add Your Resume to the Jekyll Site**: Add your "resume.md" file to the Jekyll site. You can do this by creating a new file in the "_includes" folder and using Jekyll's Liquid syntax to render your Markdown content.

7. **Customize Your Jekyll Site**: Customize your Jekyll site by modifying the layout, styles, and content. You can use HTML, CSS, and JavaScript to create a unique and professional-looking website.

8. **Push Your Changes to GitHub**: Commit your changes and push them to your GitHub repository.

9. **Enable GitHub Pages**: Enable GitHub Pages on your repository settings. This will publish your Jekyll site and make it accessible to the public.

10. **Share Your Resume**: Share the link to your resume with potential employers, colleagues, or friends. You can also include it in your email signature, LinkedIn profile, or business cards.

## Principles of Technical Writing

The practical steps described above relate to the general principles of current Technical Writing in several ways:

- **Simplicity**: Using Markdown and Jekyll simplifies the process of creating and hosting a resume. Markdown is a lightweight markup language that requires minimal formatting and styling, while Jekyll automates many tasks related to website creation and maintenance.

- **Clarity**: By using headings, lists, and tables, you can structure your resume in a clear and logical way. This makes it easy for readers to find the information they need and understand your skills and qualifications.

- **Accessibility**: Hosting your resume on GitHub Pages makes it accessible to a wide audience, including potential employers, recruiters, and collaborators. GitHub Pages is free, reliable, and easy to use, which means that anyone with an internet connection can view your resume.

- **Consistency**: By using a Markdown editor and a Jekyll theme, you can ensure consistency across your resume and website. Consistency is important in technical writing because it helps readers navigate the content and understand the structure and organization.

Overall, the practical steps described above demonstrate how Technical Writing principles can be applied to create a professional and effective resume using modern tools and technologies. By using Markdown and Jekyll, you can focus on the content and presentation of your resume, without worrying about the technical details of website creation and hosting.

Andrew Etter's book ["Modern Technical Writing: An Introduction to Software Documentation"](https://www.amazon.com/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) discusses the benefits of using Jekyll for technical documentation. 

[Jekyll](https://jekyllrb.com/) is a static site generator that allows developers to create websites without the need for a traditional web server.

In the book, Etter explains that Jekyll is an ideal tool for technical writers because it simplifies the process of creating and publishing technical documentation. He notes that Jekyll is highly customizable, allowing writers to create their own templates and layouts to suit their specific needs. Additionally, Jekyll's built-in support for Markdown makes it easy for writers to create clean, readable documentation.

Etter also recommends Jekyll for its ease of use and low maintenance requirements. Because Jekyll generates static sites, there is no need for complex server-side setups or content management systems. This means that technical writers can focus on creating great content rather than worrying about the technical details of hosting and maintaining a website.

Overall, Etter's book endorses Jekyll as a powerful and flexible tool for technical documentation that can help writers create high-quality, user-friendly documentation with minimal overhead.


## More Resources

- [Markdown Tutorial](https://www.markdowntutorial.com/): This tutorial introduces a single Markdown concept with an example and helps you practice along.

- [Modern Technical Writing](https://www.amazon.com/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS): This book by Andrew Etter provides the essential knowledge to start creating and publishing great software documentation.

- [Jekyll Themes](https://jekyllthemes.io/): This allows thousands of free themes for Jekyll created by the open source community. Here you'll find only the very best ones, hand-picked for their design and development quality.

## FAQs

1. Why is Markdown better than a word processor?
   - According to Andrew Etter, documents with any kind of validity period must be placed under version control. Using Markdown helps us understand storing documents online using version control.

2. Why is my resume not showing up?
   - Make sure your repository is in the format `username.github.io`. It may take a while for it to be published live, so the user can refresh it after 10-20 minutes and it should work.


