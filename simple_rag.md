# Unlock the Power of RAG with UClone: Build a Super-Smart Chatbot

Want a chatbot that's not just smart, but actually knows your stuff? This guide shows you how to build one using UClone and the magic of RAG (Retrieval Augmented Generation). RAG is the secret sauce that lets your chatbot pull answers directly from your documents, making it incredibly accurate and helpful. UClone makes using RAG a breeze – no coding required!

## 1. Accessing UClone Builder:

To begin, you'll need to contact the UClone Builder: [https://chat.uclone.net/uclone/messages/@uclone_builder](https://chat.uclone.net/uclone/messages/@uclone_builder)

The UClone Builder will guide you through the initial setup process for creating your new clone.


![](https://uclone-ai.github.io/uclone_contents/images/uclone_builder_thumbnail.jpg)

## 2. Providing Reference Data:

UClone offers two ways to provide reference data for your AI:

* **Google Drive Connection:**
    * Create a folder named 'uclone' in your Google Drive. Ensure the Google account associated with this Drive is the same as your UClone login email.
    * Upload your reference documents (text or PDF) into this 'uclone' folder. Only text content will be used; images and other media will be ignored. Ensure the 'uclone' folder name uses lowercase letters.
    * Share the 'uclone' folder with the UClone service account, granting "viewer" permission: `docs-crawler-dev@uclone-422018.iam.gserviceaccount.com`

![](https://uclone-ai.github.io/uclone_contents/images/share_crawler.jpg)

* **Direct File Upload:**
    * In the Bot Studio, click the 'Clip' icon within the Reference Files section.
    * Upload your reference documents (text or PDF). Only text content from PDFs will be used.
    * Click the **'Update'** button at the bottom to apply the changes after uploading all documents.


![](https://uclone-ai.github.io/uclone_contents/images/add_knowledge.jpg)

* **Enable Ability**
   * Basic RAG will be enabled after your document uploading.
   * You can enable Agentic-RAG by selecting Search Document Tool. (Optional)
![](./images/ability_new.jpg)

## 3. Confirmation and Creation:

Once you've configured your AI, click the "Continue" button to finalize the creation process. Your RAG-enabled AI will then be ready to interact with users, drawing upon the provided reference data to generate informed and relevant responses.

## 4. Agentic RAG:

UClone provide document search tools. Add instruction on your Clone to utilize agent RAG workflow. Your clone will automatically search documents when it is necessary based upon conversation context.
Take a look at the [Using Tools in UClone](./uclone_toolsd)

If you have further questions, please contact the UClone Help Desk: [https://chat.uclone.net/uclone/messages/@uclone_help_desk](https://chat.uclone.net/uclone/messages/@uclone_help_desk)

[UClone Introduction](https://docs.uclone.net/)
