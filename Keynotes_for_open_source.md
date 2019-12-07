# Keynotes for open-source

Before pushing our code to public, we usually re-organize the code to a cleaner version. The following are points we need to care about:

1. Make the **code sturcture** as simple as possible
2. **Simple interface** for the features that we implement
3. **Single entrance** for each section
4. Detailed ``README.md`` 
5. Delete all value that might **leak private information** such as local file paths.
6. If the code is **affiliated to a paper**, indicate the paper and present the link at the top of ``README.md``. Moreover, if the paper is still in submission, make sure the conference name would not appear in the code and note other demands as stated by the conference.