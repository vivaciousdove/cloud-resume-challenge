# Frontend Technical Specification

- Create a static website that serves an html resume.
- Using Codespace

## Harvard Resume Format Considerations
I am a US citizen and downloadable resumes in word/pdf format are recommended to exclude certain pieces of information. I.e. Age, Relationship, etc.

[Harvard Resume Template](https://careerservices.fas.harvard.edu/channels/create-a-resume-cv-or-cover-letter/)

![](./docs/resume-image-harvard-crc.jpg)

## Resume Format Generation

I am going to use an existing resume that was professionally generated during recent QA and Cloud bootcamp experiences.

![](./docs/resume-image-crc.jpg)

I have basic to itermediate knowledge of HTML and CSS, therefore I am using GenAI to support the code generation that I will then manually refactor to my personal specifications.

Prompt to ChatGPT5.1:

'''text
Convert this resume image into HTML.
Do not use a CSS framework.
Use the least amount of CSS tags
'''

This is the [generated output](./docs/html/11.24.25-resume-image-crc.html) that I will refactor






