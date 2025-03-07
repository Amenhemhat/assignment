## DOCUMENT HOSTING GUIDE.
#### THIS IS A GUIDE ON HOW TO PROPERLY FORMAT A DOCUMENT AND HOST IT ON A FORGE WITH STATIC WEBSITE GENERATOR.
#### PREREQUISITES
 * Intermediate to Expert level understanding of Markdown. Follow this link for a short tutorial on Markdown if you are not yet familiar with it [Markdown Tutorial](https://www.markdowntutorial.com/)
 * Basic English Reading comprehesion skills in order to be able to properly follow the instructions provided in this guide.
 * A minimum intermidiate level understanding of waht static website generators are all about. The following link provides adequate information with respect to static website generators: [Static Website Generators](https://www.youtube.com/watch?v=FQL2J7809a8)
 * Basic computer skills like typing, saving and retrieving documents, editing files, and looking for file paths on the computer.
 * You must have Python downloaded and installed in your computer. If not, find here a tutorial on how to do so: [Python download and set up](https://www.youtube.com/watch?v=yivyNCtVVDk####)
 #### INSTRUCTIONS.
  * FORMATING THE TEXT IN MARKDOWN FORMAT.
    * It is of extreme importance to format your text into Markdown. This will not only allow you to safely use static website generators to make your posts visible on the website, it will also help you automate a lot of processes that might be gruesome to repetitively do manually.
    * Your document should consider your audience, and it will set the tone of the document you are trying to ccome up with. For a resume, it should be clear that your document will be adressed to an employer, and you should therefore have a formal and professional tone in your writing  **(This is one of the main concepts in Etter's Modern Technical Writing book concerning the relationship between your writing and its intended audience)**.
    * Be straight-forward in yoour writing, trying to keep things as concise and precise as much as possible **(This is again an important aspect highlighted by Etter's book).**
    * In order to write Markdown files, you must have some form of Markdown editor, which is just the appropriate place where you can write Markdown and view its live text version. I recommend you use VScode as an editor. Find here a tutorial on how to install and set up VScode for markdown editing [VScode and Markdown tutorial](https://www.youtube.com/results?search_query=vs+code+and+markdown). Here is also a tutorial on how to download VScode and set it up properly for use [VScode download and set up guide](https://www.youtube.com/watch?v=cu_ykIfBprI)
    * After completing the prerequisite section of this file, you should have been able to go through the Markdown tutorial for which the link was provided above. This will let you format the text that you have into markdown files smoothly.
    * Once everything is complete, you can now revise and edit any aspect of your writing you think necessary to do so **(This is another important concept, revising and editing, as recommended by William Pfeiffer's book on technical documentation).**
 * SAVING THE COMPLET MARKDOWN FORMAT IN YOUR COMPUTER.
    * Once your markdown format is complete, you now have to save it on your computer. This can easily be done pressing ctrl and s on your computer, after the markdown file has been completely elaborated.
    * Make sure to keep track of the folder where you saved the markdown file, since this will be crucial for the next steps in this guide.
 * DOWNLOADING AND SETTING UP A STATIC SITE GENERATOR.
    * Now that we are done with our markdown file, we now want to deploy it on the web with our static site generator. If you watched the video for which i provide the link in the prerequisite section, you should now be familiar with what static site generators are and what they do.
    * Out of the multiple available websites out there, i recomend you use **Pelican** in Python. These will easily let you host your website. You should now have Python properly downloaded and installed in your computer, since you must have watched the tutorial provided above.
    * Within python, you will now download and use pelican. [Here](https://www.youtube.com/watch?v=fp3EjRHltcc) is a simple tutorial on how to properly download and set up pelican for your website.
 * SETTING UP A FORGE WHERE THE POST OR ARTICLE WILL BE HOSTED.
    * We now need to have a forge. This is just an environment that allows us to post our websites. There are many forges you can use, but i recommend you use GitHub. You will have to create a gitHub account, which can be done easily my entering the required information on the website, and you can then use it.
    * When your account is successfully created, you will then have to create a new repository, which is simply an environment that stores particula files for a particular project, where the directory name is usually the name of the project. In order for you to create your repository, [here](https://www.youtube.com/watch?v=-RZ03WHqkaY) is a tutorial that should help you do so.
 * CONNECTING OUR FORGE TO OUR LOCAL COMPUTER.
    * This is where we set up a relationship between our Github account and our local computer, so that we can directly access information in our GitHub account from our computer, without having to manually login to our account every time. watch the following tutorial to help you connect your GitHub account to your computer: [How to connect my Github account and repository to my computer](https://www.youtube.com/watch?v=EhxPBMQFCaI).
    * Now, we can directly access our Github account from our computer smoothly, by using git, which you should now be familiar with after watching the previous tutorial provided.
 * USING OUR STATIC SITE GENERATOR AND FORGE TO HOST THE SITE.
    * Since we both have the same operating system, following the instructions i give here will result in a successfull completion of this task.
    * Recall that you have already created your Markdown format successfully and saved it in some folder in your computer. You now need to give pelican access to this file. Go to the folder where you saved your markdown format and copy it. Paste it in the content folder found in the OS folder of your computer. pellican now has access to this folder.
    * Now go to the command line; this can be done by clicking on the research icon found at the buttom of your computer screen and typing in **cmd**
    * In the command line, type in `pelican-quickstart`and follow the instructions given. 
    * When you are asked to specify a particular URL path, type in `https/username.github.io/repository` where **username** should be your Github account username, and **repository** should be the name of the repository you created earlier. After this, press enter until the whole process is done.
    * Now, still in the command line, type in `git add.` and press enter.
    * Repeat the process for `git commit -am "First commit`
    * Repeat this process for `pelican content -s publishconf.py`
    * repeat the process for `git push origin gh-pages`.
    * If you followed the above procedure correctly, you should now be able to view all the pages stored in your local computer under the content folder in the GitHub repository to used for this process.
#### FAQS.
 * Why do i get a `git is not recognized as a command` error when i try to use git?
    * This is because you installed git and did not make it an environment variable on your computer. This is crucial if you want to be able to use git in the command line. In order to do so, please watch the following tutorial: [How to make git an environment variable in my computer?](https://www.youtube.com/watch?v=IflluA2tt14).
 * Does it matter what static site generator i use?
     * Not necessarily. You can choose any static site generator to host yor website, as far as you are comfortable with it. One thing you have to however keep in mind is that, depending what Static generator you use, you might have to make sure it is compatible to the Forge you are tring o use, since they are not always compatible with all Static site generators.
#### LIST OF HELPFUL LINKS.
* [How to set up python](https://www.youtube.com/watch?v=9o4gDQvVkLU).
* [How to download pelican with Python?](https://www.youtube.com/watch?v=fp3EjRHltcc&t=135s).
* [Markdown Tutorial](https://www.youtube.com/watch?v=_PPWWRV6gbA).
* [Downloading and setting up Git](https://www.youtube.com/watch?v=AdzKzlp66sQ).

#### CREDITS
 * Alex Choy.
