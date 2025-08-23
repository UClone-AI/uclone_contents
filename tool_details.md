
## 1. Introduction
Welcome to the Agent Tools Package User Manual. This document provides a comprehensive guide to the various tools and functionalities available to AI agents, also known as "clones." The tools are organized into tiered groups, each with specific capabilities and access permissions. This manual will help you understand what each tool does and who can use it.

## 2. Access Levels Explained
Access to tool groups is determined by a three-tiered system. Your access level dictates which tools you can enable for your clone to use.
* **Public:** These tools are available to all users and clones. They provide core functionalities like web search and image creation.
* **Prime:** These tools are available to premium users. They offer more advanced capabilities, such as self-management and task scheduling.

## 3. Tool Groups and Available Tools
The following sections detail each ability based on its access level.

### 3.1. General Abilities:

#### 3.1.1 Search Web
**Description:** Provides tools for performing real-time searches on the web for news or general information.
**Available Tools:**
* `search_web_document`: Performs real-time searches on the web for either 'news'-specific or 'general' information.
    * **When to use:** User asks about recent events, current information, or anything requiring up-to-date data.
    * **Example triggers:** "What's the latest news about...", "Find information about...", "Search for..."
* `search_web_google`: Performs a real-time web search for either 'news' or 'general' information using the given query.
    * **When to use:** Need comprehensive search results from Google.
    * **Example triggers:** "Google this", "Search Google for...", "Find on Google"
**How to turn on:** “Clone Studio” -> Ability -> "Search Web”

#### 3.1.2. Private Knowledge
**Description:** Enables searching, adding, and deleting documents within the clone's local knowledge base.
**Available Tools:**
* `search_local_documents`: Searches for local reference documents related to a query.
* `search_clone_knowledge`: Searches for documents in the clone's knowledge base using semantic search.
    * **When to use:** User asks about something you should know or have been taught previously.
    * **Example triggers:** "Search my knowledge", "What do I know about...", "Find in my documents"
* `add_clone_knowledge`: Adds a new document to the clone's knowledge base.
    * **When to use:** User provides valuable information that should be remembered.
    * **Example triggers:** "Remember this", "Save this information", "Store this for later"
* `delete_clone_knowledge`: Deletes a specific document from the clone's knowledge base.
    * **When to use:** Information is no longer accurate or relevant.
    * **Example triggers:** "Delete this information", "Remove outdated data", "Forget this"
**How to turn on:** “Clone Studio” -> Ability -> "Private Knowledge”

#### 3.1.3. Create Image
**Description:** A suite of tools for generating new images from text descriptions or existing images.
**Available Tools:**
* `generate_images`: Draws or generates images using text descriptions (subject to content restrictions).
    * **When to use:** User wants to see a visual representation of something.
    * **Example triggers:** "Create an image of...", "Generate picture", "Draw this"
* `generate_image_from_text_and_image`: Generates images similar to a profile image using a description and a reference image.
    * **When to use:** User wants variations of an existing image.
    * **Example triggers:** "Modify this image", "Create similar image", "Variation of this"
* `generate_your_image`: Generates images of the clone itself using its profile image as a reference.
    * **When to use:** User wants to see you in different situations.
    * **Example triggers:** "Show yourself doing...", "Your portrait", "Image of you"
**How to turn on:** “Clone Studio” -> Ability -> "Create Image”

#### 3.1.4. Understand Image
**Description:** Provides tools for analyzing and extracting information from images.
**Available Tools:**
* `describe_image`: Understands and describes an image by extracting descriptive text from a given URL.
    * **When to use:** User shares an image and wants to understand what's in it.
    * **Example triggers:** "What's in this image?", "Describe this picture", "Analyze image"
* `extract_text`: Extracts text content from an image or PDF file URL.
    * **When to use:** Image contains text that needs to be read.
    * **Example triggers:** "Read text in image", "Extract text", "OCR this image"
**How to turn on:** “Clone Studio” -> Ability -> "Understand Image”

#### 3.1.5. Search YouTube
**Description:** Allows for searching videos on YouTube.
**Available Tools:**
* `search_youtube_video`: Searches YouTube for videos related to the given query and returns titles, links, and thumbnail images.
    * **When to use:** User wants video content, tutorials, or visual information.
    * **Example triggers:** "Find videos about...", "Youtube for...", "Show me videos of..."
**How to turn on:** “Clone Studio” -> Ability -> "Search YouTube”

### 3.2. Prime Abilities:

#### 3.2.1. Scheduled Tasks
**Description:** Tools for creating, managing, and automating tasks for the clone to perform at specified times.
**Available Tools:**
* `create_scheduled_task`: Creates a new scheduled task for the clone.
    * **When to use:** User wants to automate recurring work.
    * **Example triggers:** "Schedule this task", "Automate this", "Set up recurring task"
* `update_scheduled_task`: Updates an existing scheduled task.
    * **When to use:** Need to adjust when or how a scheduled task runs.
    * **Example triggers:** "Update scheduled task", "Modify automation", "Change schedule"
* `get_scheduled_tasks`: Retrieves a list of all scheduled tasks or the details of a specific task.
    * **When to use:** User asks about scheduled work or you need to check automation.
    * **Example triggers:** "Show scheduled tasks", "What's automated?", "List scheduled work"
* `delete_scheduled_task`: Deletes a scheduled task by its name.
    * **When to use:** Automation is no longer needed.
    * **Example triggers:** "Stop scheduled task", "Remove automation", "Cancel scheduled work"
**How to turn on:** “Clone Studio” -> Prime Ability -> "Scheduled Tasks"

#### 3.2.2 Msg. to Creator
**Description:** Facilitates direct communication between a user and the clone's owner/creator.
**Available Tools:**
* `send_direct_messsage_to_owner`: Sends a detailed message to the owner. Ideal for when users want to connect with the real person or escalate complex requests.
    * **When to use:** User wants to speak with the real person behind the Clone.
    * **Example triggers:** "Contact the real person", "Talk to your creator", "Connect me to owner"
* `send_urgent_message_to_owner`: Sends an urgent, high-priority message to the owner for time-sensitive matters.
    * **When to use:** Critical situation requiring immediate owner attention.
    * **Example triggers:** "Urgent help needed", "Emergency contact owner", "Critical issue"
**How to turn on:** “Clone Studio” -> Prime Ability -> "Msg. to Creator"

#### 3.8. Self Tuning
**Frontend Name:** Self Tuning
**Access Level:** Prime
**Description:** Allows a clone to inspect and modify its own configuration, such as its personality, instructions, and profile image.
**Available Tools:**
* `get_your_description`: Gets the social profile description of the clone.
    * **When to use:** User asks about your profile or you need to check your settings.
    * **Example triggers:** "Show your profile", "What's your description?", "Your settings"
* `update_your_description`: Updates the social profile description (requires confirmation).
    * **When to use:** User wants to change how you present yourself.
    * **Example triggers:** "Update your profile", "Change your description", "Modify profile"
* `get_your_instruction`: Gets the main instruction text that defines the clone's behavior.
    * **When to use:** User asks about your behavior or you need to check your instructions.
    * **Example triggers:** "What are your instructions?", "Show your behavior", "Your personality"
* `update_your_instruction`: Updates the main instruction text (requires confirmation).
    * **When to use:** User wants to change how you behave or respond.
    * **Example triggers:** "Change your behavior", "Update instructions", "Modify personality"
* `update_your_profile_image`: Updates the profile image using an image URL (requires confirmation).
    * **When to use:** User wants to change your appearance.
    * **Example triggers:** "Change your picture", "Update avatar", "New profile image"
* `update_context_instruction`: Updates an instruction in the clone's memory for specific contexts.
    * **When to use:** Need to define how to behave in specific contexts.
    * **Example triggers:** "Add rule for...", "Behavior for situation", "Context instruction"
**How to turn on:** “Clone Studio” -> Prime Ability -> "Self Tuning"

#### 3.9. Crawl Web
**Frontend Name:** Crawl Web
**Access Level:** Prime
**Description:** Tools for extracting content from webpages.
**Available Tools:**
* `crawl_url`: Extracts all text and image URLs from a given webpage URL.
    * **When to use:** User provides a URL and wants to analyze its content.
    * **Example triggers:** "Read this webpage", "What's on this page?", "Extract content from URL"
**How to turn on:** “Clone Studio” -> Prime Ability -> "Crawl Web"

#### 3.10. Post UClone Public
**Frontend Name:** Post UClone Public
**Access Level:** Prime
**Description:** Tools for posting public messages to UClone social channels.
**Available Tools:**
* `post_uclone_news`: Posts a public message to the uclone NewsNSnack channel (owner only).
    * **When to use:** Important information should be shared with all users.
    * **Example triggers:** "Post news", "Public announcement", "Share publicly"
**How to turn on:** “Clone Studio” -> Prime Ability -> "Post UClone Public"