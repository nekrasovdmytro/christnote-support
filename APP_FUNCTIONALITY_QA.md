# ChristNote App - Complete Functionality Q&A

This document provides comprehensive questions and answers about all features and functionality in the ChristNote app.

---

## Table of Contents

1. [Getting Started](#getting-started)
2. [Core Notes Features](#core-notes-features)
3. [Rich Text Editor](#rich-text-editor)
4. [Dashboards](#dashboards)
5. [AI Features](#ai-features)
6. [Media & Attachments](#media--attachments)
7. [Voice Notes](#voice-notes)
8. [Reminders](#reminders)
9. [Templates](#templates)
10. [Tags & Organization](#tags--organization)
11. [Export & Import](#export--import)
12. [Settings & Configuration](#settings--configuration)
13. [Privacy & Security](#privacy--security)
14. [Troubleshooting](#troubleshooting)

---

## Getting Started

### Q: What is ChristNote?
**A:** ChristNote is a privacy-first notes app for iOS with rich text editing, reminders, voice notes, attachments, and optional AI assistance. Notes are stored locally on-device by default.

### Q: What iOS version is required?
**A:** iOS 15.0 or later is required. The app supports iPhone 13 and newer, including iPhone 17.

### Q: How do I create my first note?
**A:** Tap the floating "+" button (if enabled) or tap the "Local Notes" tab and use the create button. You can also use the template picker to create notes from templates.

### Q: How do I navigate between different sections?
**A:** Use the bottom menu bar to switch between tabs. You can hide the menu by tapping the chevron down button, and show it again by tapping the icon in the bottom-right corner.

### Q: Can I customize which tabs appear in the menu?
**A:** Yes, go to Settings → Dashboards to enable or disable specific dashboard tabs. You can also reorder tabs in Settings → Appearance → Tab Order.

---

## Core Notes Features

### Q: How do I create a new note?
**A:** 
- Tap the floating "+" button (if enabled)
- Tap "Create Note" from the template picker
- Use the app icon shortcut "New Note"
- Swipe down on the notes list and tap "Create Note"

### Q: How do I edit a note?
**A:** Tap any note in the list to open it. The editor opens automatically and you can start typing.

### Q: How do I delete a note?
**A:** 
- Swipe left on a note in the list and tap "Delete"
- Open a note, tap the menu (⋮) button, and select "Delete"
- Use multi-select mode: tap the selection icon, select notes, then tap delete

### Q: Can I recover deleted notes?
**A:** Yes! Go to Settings → Data Management → Deleted Notes to view and restore deleted notes. Notes are kept for 30 days before permanent deletion.

### Q: How do I pin a note to the top?
**A:** 
- Swipe right on a note in the list and tap "Pin"
- Open a note, tap the menu (⋮) button, and select "Pin"
- Use multi-select mode to pin multiple notes at once

### Q: How do I search for notes?
**A:** Use the search bar at the top of the notes list. You can search by note content, tags, or note names.

### Q: Can I sort my notes?
**A:** Yes, go to Settings → Notes → Sort Order. Options include:
- Most Recent (default)
- Oldest First
- Alphabetical

### Q: What are note names?
**A:** Notes can have optional names/titles. If not set, the app extracts the first line or header as a preview. You can set a custom name by tapping the note name field at the top of the editor.

### Q: How do I rename a note?
**A:** Open the note and tap on the name field at the top. You can also use the menu (⋮) → "Rename Note".

### Q: What are projects?
**A:** Projects help organize notes into groups. You can assign notes to projects and filter by project in the notes list.

### Q: How do I assign a note to a project?
**A:** Open a note, tap the menu (⋮) button, and select "Assign to Project". You can also use multi-select to assign multiple notes.

### Q: Can I filter notes by project?
**A:** Yes, use the filter bar in the notes list to select a project filter.

### Q: What is multi-select mode?
**A:** Tap the selection icon (checkmark) in the notes list toolbar to enter multi-select mode. You can then select multiple notes and perform bulk actions like delete, pin, tag, or assign to project.

### Q: How do I duplicate a note?
**A:** Open a note, tap the menu (⋮) button, and select "Duplicate Note".

### Q: Can I share notes with other apps?
**A:** Yes, open a note, tap the menu (⋮) button, and select "Share". You can export as PDF, RTF (Word-compatible), Markdown, or plain text.

### Q: What are connected notes?
**A:** Connected notes allow you to link related notes together. This is useful for organizing related content, creating knowledge graphs, or building book chapters.

### Q: How do I connect notes?
**A:** Open a note, tap the menu (⋮) button, and select "Connected Notes". Search and select notes to connect. Tap again to disconnect.

### Q: Can I see all notes connected to a specific note?
**A:** Yes, connected notes appear at the bottom of the note editor. Tap on a connected note to open it.

### Q: What are prophetic notes?
**A:** Prophetic notes are special note types for dreams, visions, and inspirations. They can be organized by type and viewed in a calendar format.

### Q: How do I create a prophetic note?
**A:** Use the "dream" template or add the "prophetic" tag. You can also filter by prophetic type in the notes list.

### Q: What is the Prophetic Calendar?
**A:** The Prophetic Calendar shows prophetic notes organized by date. Access it from the notes list or via app shortcuts.

### Q: Can I filter notes by prophetic type?
**A:** Yes, use the prophetic type filter in the notes list to filter by Dream, Vision, or Inspiration.

---

## Rich Text Editor

### Q: What editor engines are available?
**A:** The app supports two editor engines:
- iOS Native Editor (default) - Uses UITextView for native iOS editing
- HTML Editor - Alternative editor for web-based content

You can switch between them in Settings → Editor → Editor Engine.

### Q: What formatting options are available?
**A:** The editor supports:
- Headers (H1, H2, H3)
- Bold, Italic, Underline, Strikethrough
- Text highlighting (7 colors)
- Text alignment (left, center, right, justify)
- Bulleted lists
- Numbered lists
- Dividers
- Clear formatting

### Q: How do I format text?
**A:** Select text and use the formatting toolbar that appears. You can also use keyboard shortcuts:
- **Bold:** ⌘B
- **Italic:** ⌘I
- **Underline:** ⌘U

### Q: What is Focus Mode?
**A:** Focus Mode provides a distraction-free writing experience by hiding the header and other UI elements. It's enabled by default but can be toggled in Settings → Editor.

### Q: How do I exit Focus Mode?
**A:** Tap the "Exit Focus Mode" button that appears, or swipe down from the top.

### Q: Can I customize the font?
**A:** Yes, go to Settings → Editor → Font Family to choose from bundled Google fonts or system fonts.

### Q: Can I adjust line spacing?
**A:** Yes, go to Settings → Editor → Line Spacing to adjust the spacing between lines.

### Q: How do I insert images?
**A:** 
- Tap the image button in the formatting toolbar
- Use Photos picker to select images
- Paste images directly from clipboard
- Use the camera button to take photos

### Q: Can I resize images in notes?
**A:** Yes, tap an image to select it, then use the resize options:
- Small (160px)
- Medium (240px)
- Large (320px)
- Fit to width

### Q: Can I draw on images?
**A:** Yes, select an image and tap "Draw on Image" to open the drawing editor.

### Q: How do I insert a divider?
**A:** Tap the divider button in the formatting toolbar, or type "---" and it will convert to a divider.

### Q: What are highlights?
**A:** Highlights allow you to mark important text with colored backgrounds. There are 7 highlight colors available.

### Q: How do I highlight text?
**A:** Select text and tap the highlight button in the formatting toolbar. Choose a color from the picker.

### Q: Can I remove highlighting?
**A:** Yes, select highlighted text and tap "Clear Highlight" or choose "None" from the highlight color picker.

### Q: How do I create lists?
**A:** Tap the list button in the formatting toolbar and choose "Bulleted List" or "Numbered List". You can also start typing "- " or "1. " to auto-create lists.

### Q: Can I nest lists?
**A:** Yes, indent list items using the indent buttons or by tapping Tab on the keyboard.

### Q: How do I clear all formatting?
**A:** Select text and tap "Clear Formatting" in the formatting toolbar.

### Q: Does the editor support Markdown?
**A:** The editor doesn't use Markdown syntax during editing, but you can export notes as Markdown. Some Markdown features are supported through the formatting toolbar.

### Q: Can I undo/redo changes?
**A:** Yes, shake your device or use the undo/redo buttons if available. Standard iOS text editing undo/redo works.

### Q: How do I copy formatted text?
**A:** Select text and use the standard copy gesture or menu. Formatted text is preserved when pasting within the app.

### Q: Can I paste plain text only?
**A:** Yes, when pasting, you'll see paste options. Choose "Paste as Plain Text" to remove formatting.

---

## Dashboards

### Q: What are dashboards?
**A:** Dashboards are specialized views that organize and display specific types of content:
- Highlights Dashboard
- Audio Dashboard
- Attachments Dashboard
- Secrets Dashboard
- Todo Dashboard
- Connected Notes Dashboard
- AI Communications Dashboard
- AI Overview Dashboard
- Canvas Dashboard
- Gantt Dashboard

### Q: How do I enable/disable dashboards?
**A:** Go to Settings → Dashboards and toggle the dashboards you want to use.

### Q: What is the Highlights Dashboard?
**A:** The Highlights Dashboard shows all highlighted text from your notes, organized by color. Useful for reviewing important passages.

### Q: How do I access highlighted text?
**A:** Open the Highlights Dashboard tab, select a highlight color, and tap on any highlight to open the source note.

### Q: What is the Audio Dashboard?
**A:** The Audio Dashboard shows all voice recordings attached to notes. You can play, rename, and manage recordings.

### Q: How do I play a voice recording?
**A:** Open the Audio Dashboard, tap on a recording to play it. The player appears at the bottom with controls.

### Q: Can I rename voice recordings?
**A:** Yes, tap the menu (⋮) next to a recording in the Audio Dashboard and select "Rename".

### Q: What is the Attachments Dashboard?
**A:** The Attachments Dashboard lists all file attachments (PDFs, images, etc.) across all notes.

### Q: How do I open an attachment?
**A:** Tap on an attachment in the Attachments Dashboard to open it. PDFs open in Quick Look.

### Q: What is the Secrets Dashboard?
**A:** The Secrets Dashboard shows all notes tagged as "secret". These notes are encrypted and require authentication to view.

### Q: How do I create a secret note?
**A:** Add the "secret" tag to a note, or use the "Create Secret Note" option. You'll be prompted to set a password.

### Q: How do I unlock a secret note?
**A:** Tap on a secret note and enter your password or use Face ID/Touch ID if enabled.

### Q: What is the Todo Dashboard?
**A:** The Todo Dashboard shows all notes with todo lists, organized by completion status.

### Q: How do I create a todo list?
**A:** Use the "todo" template or add the "todo" tag to a note. Then tap the todo button in the editor toolbar.

### Q: Can I mark todos as complete?
**A:** Yes, tap the checkbox next to each todo item to mark it complete or incomplete.

### Q: What is the Connected Notes Dashboard?
**A:** The Connected Notes Dashboard shows a visual graph of all connected notes, helping you see relationships between notes.

### Q: What is the AI Communications Dashboard?
**A:** The AI Communications Dashboard shows all AI interactions and conversations stored in your notes.

### Q: What is the AI Overview Dashboard?
**A:** The AI Overview Dashboard uses AI to analyze and categorize all your notes, grouping them by meaning and themes.

### Q: How do I generate an AI Overview?
**A:** Open the AI Overview Dashboard and tap "Generate Overview". You can customize the prompt or use the default.

### Q: What is the Canvas Dashboard?
**A:** The Canvas Dashboard shows all canvas boards - visual workspaces for organizing notes spatially.

### Q: How do I create a canvas?
**A:** Open the Canvas Dashboard and tap "New Canvas". You can add notes to canvases by dragging or using the menu.

### Q: What is the Gantt Dashboard?
**A:** The Gantt Dashboard collects all notes that contain project tasks and shows them as Gantt charts, so you can see timelines, milestones, and progress across your projects in one place.

### Q: How do I create a Gantt chart?
**A:** Create or open a note with tasks (for example using a Gantt or project template), then open the Gantt view from the Tasks & Gantt area or via the Gantt Dashboard. You can export your chart as PDF, CSV, or JSON for sharing, printing, and backup.

---

## AI Features

### Q: Does the app require AI?
**A:** No, AI features are completely optional. The app works fully without AI configured.

### Q: What AI providers are supported?
**A:** The app supports:
- OpenAI (GPT models)
- Claude (Anthropic)
- DeepSeek

You can only use one provider at a time.

### Q: How do I set up AI?
**A:** Go to Settings → AI Interactions → Setup. Enter your API key. See `Docs/AI_SETUP.md` for detailed instructions.

### Q: Where are API keys stored?
**A:** API keys are stored securely in the iOS Keychain, not in plain text.

### Q: How do I ask AI a question in a note?
**A:** Open a note, tap the AI button (sparkles icon) in the toolbar, type your question, and tap "Ask".

### Q: What can I do with AI responses?
**A:** You can:
- Copy the response
- Append to note
- Replace note content
- Save the conversation

### Q: What are AI quick actions?
**A:** Quick actions appear in the editor toolbar when AI is configured:
- Summarize
- Improve Writing
- Translate
- Format with AI

### Q: How do I use AI quick actions?
**A:** Select text (or leave empty for the whole note) and tap a quick action button. The AI will process your selection.

### Q: What is AI Interpretation?
**A:** AI Interpretation analyzes prophetic notes (dreams, visions) and provides insights. Access it from the note menu.

### Q: Can I customize AI prompts?
**A:** Yes, go to Settings → AI Interactions to customize prompts for different actions.

### Q: What is AI Search?
**A:** AI Search allows you to search notes using natural language queries, finding notes by meaning rather than exact text matches.

### Q: How do I use AI Search?
**A:** Tap the AI Search button in the notes list and enter your query in natural language.

### Q: Can I see my AI usage/history?
**A:** Yes, the AI Communications Dashboard shows all AI interactions. You can also view AI history per note in the note menu.

### Q: Are AI conversations saved?
**A:** Yes, AI conversations are saved in notes. You can view them in the AI Communications Dashboard or within individual notes.

### Q: Can I delete AI conversations?
**A:** Yes, open a note with AI conversations, tap the menu, and select "Delete AI Conversation" or remove individual messages.

---

## Media & Attachments

### Q: What file types can I attach?
**A:** You can attach:
- Images (JPEG, PNG, HEIC)
- PDFs
- Other document types supported by iOS

### Q: How do I attach a file to a note?
**A:** 
- Open a note, tap the attachments button
- Select "Add Attachment"
- Choose from Files app, Photos, or Camera

### Q: Can I attach multiple files at once?
**A:** Yes, use the "Add Multiple Attachments" option to select multiple files.

### Q: How do I view attachments?
**A:** Tap the attachments button in a note to see all attachments. Tap on an attachment to open it.

### Q: Can I export all attachments?
**A:** Yes, go to Settings → Data Management → Export All Attachments.

### Q: How do I delete an attachment?
**A:** Open the attachments sheet in a note, swipe left on an attachment, and tap "Delete".

### Q: Are attachments stored locally?
**A:** Yes, all attachments are stored locally on your device.

### Q: Can I resize images after inserting them?
**A:** Yes, tap an image to select it, then use the resize options in the menu.

### Q: Can I draw on images?
**A:** Yes, select an image and tap "Draw on Image" to open the drawing editor.

### Q: How do I insert images from Photos?
**A:** Tap the image button in the toolbar, then select "Photos" and choose images from your photo library.

### Q: Do I need to grant photo permissions?
**A:** Yes, the app will request permission the first time you try to access photos.

### Q: Can I take photos directly in the app?
**A:** Yes, tap the camera button in the image picker to take a photo.

### Q: How do I export all photos from notes?
**A:** Go to Settings → Data Management → Export All Photos.

---

## Voice Notes

### Q: How do I record a voice note?
**A:** 
- Open a note and tap the microphone button in the toolbar
- Or create a note with the "voice-note" tag

### Q: Can I pause and resume recording?
**A:** Yes, the voice recorder has pause/resume controls.

### Q: How do I play a voice recording?
**A:** Tap the play button on a voice recording in a note, or open the Audio Dashboard to see all recordings.

### Q: Can I rename voice recordings?
**A:** Yes, tap the menu (⋮) next to a recording and select "Rename".

### Q: How do I delete a voice recording?
**A:** Tap the menu (⋮) next to a recording and select "Delete".

### Q: Can I export voice recordings?
**A:** Yes, go to Settings → Data Management → Export All Voice Recordings.

### Q: Where are voice recordings stored?
**A:** Voice recordings are stored locally on your device, attached to notes.

### Q: What audio format is used?
**A:** Recordings are stored in a standard iOS audio format (typically M4A).

### Q: Can I attach multiple voice recordings to one note?
**A:** Yes, you can record multiple voice notes in a single note.

### Q: What is Quick Audio (Quick Record)?
**A:** Quick Audio is a fast way to start a new voice recording from Siri, the Shortcuts app, or Control Center. It opens a lightweight recording sheet in ChristNote so you can capture ideas without navigating the full app.

### Q: How do I use Quick Audio?
**A:** Add the "Open Quick Record" shortcut from the Shortcuts app or ask Siri to "Quick record in ChristNote". The app opens directly to the quick audio recorder and saves the recording locally with your notes.

---

## Reminders

### Q: How do I add a reminder to a note?
**A:** 
- Swipe right on a note in the list and tap "Reminder"
- Open a note, tap the menu (⋮), and select "Add Reminder"
- Use multi-select to add reminders to multiple notes

### Q: Can I set recurring reminders?
**A:** Yes, when creating a reminder, toggle "Repeat Daily" for daily reminders.

### Q: How do I edit a reminder?
**A:** Go to Settings → Reminders, tap on a reminder, and edit the date/time.

### Q: How do I delete a reminder?
**A:** Go to Settings → Reminders, swipe left on a reminder, and tap "Delete".

### Q: What happens when a reminder fires?
**A:** You'll receive a notification. Tapping the notification opens the linked note directly.

### Q: Do reminders work when the app is closed?
**A:** Yes, reminders use iOS notifications and work even when the app is closed.

### Q: Can I see all my reminders?
**A:** Yes, go to Settings → Reminders to see a list of all reminders.

### Q: Do I need to grant notification permissions?
**A:** Yes, the app will request notification permission when you create your first reminder.

---

## Templates

### Q: What are templates?
**A:** Templates are pre-formatted note structures that help you create notes quickly with consistent formatting.

### Q: How do I use a template?
**A:** Tap the template picker button (or swipe down on notes list) and select a template. The note opens with the template content.

### Q: What templates are available?
**A:** Default templates include:
- Blank Note
- Dream
- Todo List
- And more (customizable)

### Q: Can I create custom templates?
**A:** Yes, go to Settings → Templates → Manage Templates to create, edit, or delete templates.

### Q: How do I edit a template?
**A:** Go to Settings → Templates → Manage Templates, tap on a template, and select "Edit".

### Q: Can I delete templates?
**A:** Yes, go to Settings → Templates → Manage Templates and swipe left on a template to delete it.

### Q: Are templates localized?
**A:** Yes, templates support multiple languages. You can set the language when creating a template.

---

## Tags & Organization

### Q: How do I add tags to a note?
**A:** 
- Open a note and tap the tags button
- Or swipe right on a note in the list and tap "Tags"
- Use multi-select to tag multiple notes

### Q: How do I remove a tag?
**A:** Open the tag editor and tap the X next to a tag, or swipe left on a tag in the tag bar.

### Q: Can I filter notes by tag?
**A:** Yes, tap on a tag in the tag bar at the top of the notes list to filter.

### Q: How do I see all tags?
**A:** Tags appear in the tag bar above the notes list. You can also go to Settings → Tags to manage tags.

### Q: Can I rename a tag?
**A:** Yes, go to Settings → Tags, tap on a tag, and select "Rename".

### Q: Can I delete a tag?
**A:** Yes, go to Settings → Tags, swipe left on a tag, and tap "Delete". You'll be asked to confirm.

### Q: What are protected tags?
**A:** Protected tags (like "markdown", "dream", "secret") have special functionality and cannot be deleted.

### Q: How do I use bulk tagging?
**A:** Enter multi-select mode, select multiple notes, then tap "Add Tags" to tag them all at once.

### Q: Can I assign colors to tags?
**A:** Yes, some tags have associated colors. You can filter by color in the notes list.

### Q: How do I filter by color?
**A:** Use the color filter in the filter bar above the notes list.

---

## Export & Import

### Q: How do I export a single note?
**A:** Open a note, tap the menu (⋮), and select "Export". Choose PDF, RTF, Markdown, or Plain Text.

### Q: How do I export all notes?
**A:** Go to Settings → Data Management → Export Notes. You can export as JSON with optional encryption.

### Q: Can I encrypt my exports?
**A:** Yes, when exporting, toggle "Encrypt Export" and set a password.

### Q: How do I import notes?
**A:** Go to Settings → Data Management → Import Notes and select a JSON file. If encrypted, enter the password.

### Q: Can I import from CSV/Excel?
**A:** Yes, go to Settings → Data Management → Import from CSV. The CSV should have columns for title, content, tags, etc.

### Q: What CSV format is required?
**A:** The CSV should have columns: Title, Content, Tags (comma-separated), Created Date, etc. See Settings for the exact format.

### Q: Can I export secrets separately?
**A:** Yes, go to Settings → Data Management → Export Secrets to export only secret notes (encrypted).

### Q: How do I import secrets?
**A:** Go to Settings → Data Management → Import Secrets and select an encrypted secrets file.

### Q: What formats can I export to?
**A:** 
- PDF (for sharing/printing)
- RTF (Word-compatible)
- Markdown (.md)
- Plain Text (.txt)
- JSON (for backup/import)

### Q: Can I export photos separately?
**A:** Yes, go to Settings → Data Management → Export All Photos.

### Q: Can I export voice recordings separately?
**A:** Yes, go to Settings → Data Management → Export All Voice Recordings.

### Q: Can I export attachments separately?
**A:** Yes, go to Settings → Data Management → Export All Attachments.

---

## Settings & Configuration

### Q: How do I access settings?
**A:** Tap the Settings tab in the bottom menu bar, or use the app shortcut "Open Settings".

### Q: What can I configure in settings?
**A:** Settings include:
- App Presets (quick configuration)
- Storage & Sync (iCloud)
- Reminders
- Writing Analytics
- Appearance (theme, fonts, layout)
- Dashboards (enable/disable)
- Notes (sort order, filters)
- Templates
- Tags
- Editor Toolbar
- Widgets
- App Icon Shortcuts
- Advanced Options
- PDF Settings
- Data Management
- Prayer Settings
- Web Notes
- Legal & Privacy
- About

### Q: What are App Presets?
**A:** App Presets are pre-configured settings bundles that quickly set up the app for specific use cases (e.g., "Writer", "Student", "Ministry").

### Q: How do I use an App Preset?
**A:** Go to Settings → App Presets and select a preset. Your settings will be updated automatically.

### Q: Can I create custom App Presets?
**A:** Yes, configure your settings, then go to Settings → App Presets → Save Current Configuration as Preset.

### Q: How do I enable iCloud sync?
**A:** Go to Settings → Storage & Sync → iCloud Sync and toggle it on. You'll need to be signed into iCloud.

### Q: What is Writing Analytics?
**A:** Writing Analytics tracks your writing statistics like word count, notes created, writing streaks, etc.

### Q: Can I customize the appearance?
**A:** Yes, go to Settings → Appearance to configure:
- Theme (Light/Dark/Auto)
- Font Family
- Font Size
- Line Spacing
- Tab Order
- Menu Visibility

### Q: How do I change the language?
**A:** Go to Settings → Appearance → Language and select your preferred language.

### Q: What languages are supported?
**A:** The app supports multiple languages. Check Settings → Appearance → Language for available options.

### Q: Can I customize the editor toolbar?
**A:** Yes, go to Settings → Editor Toolbar to show/hide specific buttons.

### Q: How do I configure widgets?
**A:** Go to Settings → Widgets to configure widget settings and create widget shortcuts.

### Q: What are App Icon Shortcuts?
**A:** App Icon Shortcuts allow you to add quick actions to your home screen. Long-press the app icon to see shortcuts.

### Q: How do I configure App Icon Shortcuts?
**A:** Go to Settings → App Icon Shortcuts to enable/disable specific shortcuts.

### Q: What advanced options are available?
**A:** Advanced options include:
- Debug settings
- Performance options
- Experimental features

### Q: Can I reset all settings?
**A:** Yes, go to Settings → Reset Settings. This will restore default settings but won't delete your notes.

### Q: How do I delete all notes?
**A:** Go to Settings → Data Management → Delete All Notes. You'll need to type "DELETE" to confirm.

### Q: Can I delete all connections between notes?
**A:** Yes, go to Settings → Data Management → Delete All Connections.

### Q: Can I delete all canvases?
**A:** Yes, go to Settings → Data Management → Delete All Canvases.

---

## Privacy & Security

### Q: Where are my notes stored?
**A:** Notes are stored locally on your device by default. You can optionally enable iCloud sync.

### Q: Are my notes encrypted?
**A:** Regular notes are stored in plain text locally. Secret notes are encrypted with a password you set.

### Q: Can I encrypt all my notes?
**A:** You can encrypt exports, but regular notes are stored unencrypted for performance. Use secret notes for sensitive content.

### Q: Does the app collect data?
**A:** No, the app is privacy-first and doesn't collect user data. All data stays on your device.

### Q: What about AI features?
**A:** When using AI features, your content is sent to the AI provider you configure. Review their privacy policy. AI is completely optional.

### Q: Are API keys secure?
**A:** Yes, API keys are stored in the iOS Keychain, which is encrypted and secure.

### Q: Can I use the app offline?
**A:** Yes, the app works fully offline. Only AI features require internet connectivity.

### Q: What permissions does the app need?
**A:** The app may request:
- Photo Library (to insert images)
- Camera (to take photos)
- Notifications (for reminders)
- Microphone (for voice notes)

All permissions are optional and only requested when needed.

---

## Troubleshooting

### Q: My notes aren't syncing to iCloud
**A:** 
- Check that iCloud is enabled in Settings → Storage & Sync
- Ensure you're signed into iCloud on your device
- Check iCloud storage space
- Try toggling iCloud sync off and on

### Q: The app is slow or laggy
**A:** 
- Try closing and reopening the app
- Check if you have many notes (consider archiving old ones)
- Disable unused dashboards
- Check available device storage

### Q: I can't find a note I created
**A:** 
- Check if filters are applied (tags, colors, search)
- Check if the note was deleted (go to Deleted Notes)
- Try searching with different keywords
- Check if the note is in a different project

### Q: Voice recordings aren't playing
**A:** 
- Check device volume
- Ensure the recording file exists (check Audio Dashboard)
- Try restarting the app
- Check if the note wasn't deleted

### Q: Images aren't loading
**A:** 
- Check photo library permissions
- Ensure images weren't deleted from Photos
- Try re-inserting the image
- Check available device storage

### Q: Reminders aren't working
**A:** 
- Check notification permissions in iOS Settings
- Ensure reminders are enabled in Settings → Reminders
- Check that notification time hasn't passed
- Verify device date/time is correct

### Q: AI features aren't working
**A:** 
- Check that AI is configured in Settings → AI Interactions
- Verify your API key is correct
- Check internet connectivity
- Review API usage limits with your provider

### Q: I forgot my secret note password
**A:** Unfortunately, secret notes are encrypted and cannot be recovered without the password. Make sure to remember or securely store your password.

### Q: The app crashed
**A:** 
- Try restarting the app
- Check for app updates
- If persistent, try resetting settings (this won't delete notes)
- Contact support with crash details

### Q: Can't export notes
**A:** 
- Check available device storage
- Ensure you have permission to save files
- Try exporting to a different location
- Check if the export file format is supported

### Q: Import isn't working
**A:** 
- Verify the file format is correct (JSON or CSV)
- Check if the file is encrypted (enter password if needed)
- Ensure the file isn't corrupted
- Check available device storage

### Q: Templates aren't showing
**A:** 
- Go to Settings → Templates to verify templates exist
- Try creating a new template
- Check if templates were accidentally deleted

### Q: Tags aren't appearing
**A:** 
- Check Settings → Tags to see if tags exist
- Try creating a new tag
- Verify filters aren't hiding tagged notes

---

## Additional Features

### Q: What are Canvas Boards?
**A:** Canvas Boards are visual workspaces where you can organize notes spatially, like a whiteboard or mind map.

### Q: How do I create a Canvas Board?
**A:** Open the Canvas Dashboard and tap "New Canvas". You can then add notes by dragging or using the menu.

### Q: Can I add notes to multiple canvases?
**A:** Yes, a note can be added to multiple canvas boards.

### Q: What is Web Notes?
**A:** Web Notes allows you to access any online note-taking service (like Notion, Google Keep) directly from the app.

### Q: How do I set up Web Notes?
**A:** Go to Settings → Web Notes and enter the URL of your web notes service.

### Q: What is the Daily Blessing?
**A:** The Daily Blessing is a welcome screen that can appear on app launch, showing inspirational content.

### Q: Can I disable the Daily Blessing?
**A:** Yes, go to Settings → Appearance to disable it, or dismiss it when it appears.

### Q: What are Writing Analytics?
**A:** Writing Analytics tracks statistics like:
- Total notes created
- Total words written
- Writing streaks
- Notes per day/week/month

### Q: Where can I see Writing Analytics?
**A:** Go to Settings → Writing Analytics to view your statistics.

### Q: What are App Icon Shortcuts?
**A:** App Icon Shortcuts are quick actions accessible by long-pressing the app icon on your home screen.

### Q: What shortcuts are available?
**A:** Available shortcuts include:
- New Note
- New Dream
- Open Local Notes
- Open Secrets
- Open Todos
- Open Settings
- And more

### Q: Can I use widgets?
**A:** Yes, the app supports iOS widgets. Go to Settings → Widgets to configure widget settings.

### Q: What is Dynamic Island support?
**A:** On iPhone 14 Pro and newer, the app can show note information in the Dynamic Island.

### Q: How do I enable Dynamic Island?
**A:** Go to Settings → Advanced → Dynamic Island (if available on your device).

### Q: What is the Recent Work feature?
**A:** Recent Work shows your recently edited notes for quick access.

### Q: How do I access Recent Work?
**A:** Tap the "Recent Work" button in the notes list toolbar.

---

## Tips & Best Practices

### Q: How can I organize my notes better?
**A:** 
- Use tags consistently
- Create projects for related notes
- Use templates for common note types
- Connect related notes
- Pin important notes

### Q: What's the best way to use secret notes?
**A:** 
- Use a strong, memorable password
- Consider using Face ID/Touch ID for convenience
- Don't forget your password (it can't be recovered)
- Use secret notes only for truly sensitive content

### Q: How can I improve writing productivity?
**A:** 
- Use Focus Mode for distraction-free writing
- Enable Writing Analytics to track progress
- Use templates for common formats
- Set up reminders for regular writing

### Q: What's the best way to use AI features?
**A:** 
- Use AI for brainstorming and improvement
- Review AI suggestions before accepting
- Save important AI conversations
- Be mindful of API costs

### Q: How should I back up my notes?
**A:** 
- Regularly export notes (Settings → Export Notes)
- Enable iCloud sync for automatic backup
- Export to multiple locations
- Consider encrypting exports for sensitive content

### Q: Can I use the app for book writing?
**A:** Yes! The app is great for book writing:
- Use connected notes for chapters
- Use templates for consistent formatting
- Use the Canvas Dashboard for visual organization
- Export chapters as needed

---

## Support & Resources

### Q: Where can I get help?
**A:** Check the documentation files in the app or contact support through the app settings.

### Q: Is there documentation?
**A:** Yes, see:
- `README.md` - Basic information
- `FEATURES.md` - Feature overview
- `Docs/AI_SETUP.md` - AI setup guide
- This Q&A document

### Q: How do I report a bug?
**A:** Contact support through the app or report issues via the appropriate channels.

### Q: Can I request features?
**A:** Feature requests can be submitted through support channels.

---

*Last Updated: February 2026*
*App Version: Check Settings → About for current version*
