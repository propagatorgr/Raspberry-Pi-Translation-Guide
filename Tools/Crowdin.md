# How to use Crowdin

Each project in Crowdin has a home page which provides a description of the project and a list the available languages:

![screenshot](images/Crowdin-project-page.png)

Please read the description as it may contain some important information about the project. Then, click the icon for your language, and you will be taken to a screen looking like the image below. Here you’ll find all the files within the project that need translating. Note the progress bars on the right, which indicate the progress of translation (blue) or review (green).

![screenshot](images/Crowdin_progress.png)

## Translating files

If the progress bar next to the file is empty, it means the file has not been translated yet. You will need to open th file in **Translation Mode** Click the three dots next to your chosen file’s progress bar and select **Translate**. 

![screenshot](images/Crowdin_open_translation_mode.png)

+ You will be taken to Crowdin Editor

![screenshot](images/Crowdin_editor.png)

+ In the left-hand panel (1), you will see the English source text. The heading of the section to be translated is highlighted in yellow (here it is ‘Introduction’), and the segments of the text that are not yet translated are highlighted in red.

+ Click on a segment to select it for translation. The selected segment will appear in the top middle panel (2), which is the translation area where you can add/edit the translation. 

+ Some words in the translation area might be underlined with a dotted line, which means that there is a glossary entry for that word:

![screenshot](images/Crowdin_glossary.png)

+ Hover over the word with your mouse to see the suggestion. It might be a tip on how to translate the word, or a reminder for you that the word should not be translated:

![screenshot](images/Crowdin_glossary2.png)

+ When you’re happy with your translation, click **Save**. As soon as you translate and save a segment, its colour in the left-hand panel will change to green:

![screenshot](images/Crowdin_translated.png)

+ The next segment of the text will automatically appear in the translation area. If the segment is untranslatable (for example, it’s a name of a file, a proper noun such as CoderDojo, or a URL), you can click the **Copy source** icon at the bottom of the translation area: 

![screenshot](images/Crowdin_copy_source.png)

+ The bottom panel in the middle of the screen (3) offers you suggestions for your translation, which are based on our previous translations, Crowdin global translation memory, or machine translation. Feel free to use the suggestions, but please be careful and always review them, as they may contain errors or may be unsuitable for your context. Click on a suggestion to select it, and it will be added to the translation area automatically.

+ You can add comments or questions relating to a given segment in the panel on the right (4).

+ After you translate and save the last segment in the file, the following pop-up window will appear:

![screenshot](images/Crowdin_finished.png)

+ Clicking **Open Next** will open the next file in the folder, while clicking **Select Another File** will allow you to select a different file from the folder. To continue working on the current file, close the window by clicking on the X in its top right-hand corner.

+ When you're finished with translating, you can exit the Crowdin Editor by clicking the green icon in the top left-hand corner of the screen:

![screenshot](images/Crowdin_back.png)

+ Don't forget to mark the translation as `Finished` in the spreadsheet provided by our translation manager. This will let others know that the project is ready to be reviewed.

## Reviewing files

Once the translation of a file is finished, its progress bar will be blue:

![screenshot](images/Crowdin_progress_blue.png)

+ You can review a file by opening it in Proofreading Mode: click on the three dots located to the right of the file’s progress bar, and select **Open in Proofreading Mode**.

![screenshot](images/Crowdin_proofreading.png)

+ The file will open in the Crowdin Editor:

![screenshot](images/Crowdin_proofreading_mode.png)

+ The panel on the right (3) shows the different translations that have been suggested for a sentence. This might include machine translation, which will have the Raspberry Pi logo.

+ Please click the **tick** sign next to the translation that you prefer. If you think all of the suggestions are incorrect, please suggest your own translation by clicking on the current translation (2) and making changes.

+ After approving/changing all translated segments of the file, you can exit Crowdin Editor by clicking the green icon in the top left-hand corner of the screen.

+ Select another file for review until you have approved all translations in the project. You can track your progress using the review progress bars next to the files – look out for green colour (blue indicates translation progress). Hovering over the progress bar with your mouse will show you more details.

![screenshot](images/Crowdin_progress_green.png)

For more information on using Crowdin Editor, please see: 
https://support.crowdin.com/online-editor/

+ Don't forget to mark the review as `Finished` in the spreadsheet provided by our translation manager. This will let our team know that the project is ready to be uploaded to our website.
