# StudyCards User Manual

**Version 1.1**  
**Platforms:** iOS 18+ • macOS 16+

---

## Table of Contents

1. [Welcome](#1-welcome)
2. [Getting Started](#2-getting-started)
3. [Organization and Sorting](#3-organization-and-sorting)
4. [Study Mode](#4-study-mode)
5. [Import and Export](#5-import-and-export)
6. [Sharing Flashcards](#6-sharing-flashcards)
7. [Settings](#7-settings)
8. [Tips](#8-tips)

---

## 1. Welcome

Welcome to **StudyCards** — a powerful and elegant flashcard app for iOS and macOS. Create, manage, and study your flashcards with support for LaTeX formulas, images, and seamless import/export capabilities.

<img src="screenshots/ios/main.png" alt="StudyCards — iOS" width="500">
<img src="screenshots/macos/main.png" alt="StudyCards — macOS" width="500">

**Key Features:**

- **Flashcard groups:** organize your cards by topic or subject.
- **Complete flashcards:** each card has a front and back with support for text, LaTeX formulas, and images.
- **Manual reordering:** drag flashcards to change their order within a group.
- **Group editing:** edit or delete groups from the context menu (long press).
- **Sorting and search:** sort and search groups by name, date, or flashcard count.
- **Study mode:** rate your knowledge with Easy/Unsure/Didn't Know.
- **Import and export:** transfer your cards via CSV or JSON files (with embedded base64 images).
- **Share:** send your flashcards via email, WhatsApp, AirDrop, and more.
- **Customizable settings:** appearance, language, and study order.
- **Adaptive design:** automatically adapts to iPhone, iPad, and Mac.

### Requirements

- iOS 18.0 or later / macOS 16.0 or later.
- Internet connection only required for LaTeX formula rendering (MathJax).

---

## 2. Getting Started

### 2.1 Creating a Group

Groups help you organize your flashcards by topic, subject, or category.

**Steps:**

1. Open StudyCards.
2. Tap the **+** button on the main screen.
3. Enter a name for your group (e.g., "Spanish Vocabulary", "Math Formulas").
4. Optionally, add a description to identify the group's content.
5. Tap **Save** to confirm.

<img src="screenshots/ios/create_group.png" alt="Create Group" width="500">

<img src="screenshots/macos/create_group.png" alt="Create Group - macOS" width="500">

**Tips for organizing groups:**

- Use descriptive names for easy identification.
- Consider creating groups by subject, chapter, or difficulty level.
- You can create as many groups as you need.

### 2.2 Editing or Deleting a Group

You can edit or delete a group directly from the list.

**On iOS:**

1. Long press on the group name until the context menu appears.
2. Select **Edit** to modify the name or description.
3. Select **Delete** to remove the group and all its flashcards.

**On macOS:**

1. Right-click on the group name.
2. Select **Edit** or **Delete**.

> **Warning:** Deleting a group permanently removes all its flashcards. Make sure to export them first if you need a backup.

### 2.3 Creating a Flashcard

Once inside a group, you can start adding flashcards.

**Steps:**

1. Open a group by tapping on it.
2. Tap the **+** button.
3. Enter the **front** text (the question or prompt).
4. Enter the **back** text (the answer or explanation).
5. Optionally, add an **image** by tapping **Select Image**.
6. Optionally, add a **LaTeX formula** using `$...$` (inline) or `$$...$$` (block).
7. Tap **Save**.

<img src="screenshots/ios/create_card.png" alt="Create Flashcard" width="500">

<img src="screenshots/macos/create_card.png" alt="Create Flashcard - macOS" width="500">

### 2.4 Adding LaTeX Formulas

StudyCards supports LaTeX rendering via MathJax for mathematical and scientific notation.

| Type | Syntax | Example |
|------|--------|---------|
| Inline | `$f(x) = x^2$` | The function is $f(x) = x^2$ |
| Block | `$$\int_0^1 x^2 \, dx$$` | Formula on a separate line |

**LaTeX examples:**

- **Quadratic equation:** `$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$`
- **Pythagorean theorem:** `$a^2 + b^2 = c^2$`
- **Definite integral:** `$$\int_a^b f(x)\,dx = F(b) - F(a)$$`

> **Note:** Formulas are automatically rendered when saving the card and during study sessions.

### 2.5 Adding Images

You can attach images to your flashcards for visual learning.

**Steps:**

1. When creating or editing a flashcard, tap **Select Image**.
2. Choose to take a new photo or select from your library.
3. The image will be attached to the flashcard.

<img src="screenshots/ios/add_image.png" alt="Add Image" width="500">

<img src="screenshots/macos/add_image.png" alt="Add Image - macOS" width="500">

> **Note:** Images are automatically resized to a maximum of 1024 pixels to optimize storage. When exporting as JSON, images are included in base64 format.

### 2.6 Deleting a Flashcard

You can delete a flashcard by swiping left.

**Steps:**

1. In the flashcard list, swipe the card to the left.
2. A red **Delete** button will appear.
3. Tap **Delete** to confirm.

<img src="screenshots/ios/swipe_delete.png" alt="Swipe to Delete" width="500">

<img src="screenshots/macos/swipe_delete.png" alt="Swipe to Delete - macOS" width="500">

> **Warning:** Deletion is permanent. Make sure to export your cards before deleting if you don't have a backup.

---

## 3. Organization and Sorting

### 3.1 Manually Reordering Flashcards

You can change the order of flashcards within a group by dragging them.

**On iOS:**

1. Open the group with the flashcards you want to reorder.
2. Tap **Edit** in the toolbar (top left corner).
3. Drag handles ⟟ will appear next to each flashcard.
4. Drag the flashcard to the desired position.
5. Tap **Done** to save the new order.

**On macOS:**

1. Open the group with the flashcards you want to reorder.
2. Tap the **Reorder** button (↕ icon) in the toolbar.
3. Drag the flashcard to the desired position.
4. Tap **Done** to exit reorder mode.

> **Note:** The manual order is preserved when exporting and importing flashcards.

### 3.2 Sorting Groups

You can sort the group list by different criteria.

**Steps:**

1. Tap the sort button (↕ icon) in the toolbar.
2. Select one of the sorting criteria:

| Criterion | Description |
|-----------|-------------|
| **Name (A-Z)** | Ascending alphabetical order |
| **Name (Z-A)** | Descending alphabetical order |
| **Newest** | Most recently created groups first |
| **Oldest** | Oldest groups first |
| **Number of flashcards** | Groups with the most flashcards first |

> **Note:** Sorting applies to both the **Groups** and **Study** sections.

### 3.3 Searching for Groups

**On iOS:**

1. Pull down on the group list to reveal the search bar.
2. Type the name of the group you're looking for.

**On macOS:**

1. Use the search bar at the top of the sidebar.
2. Type the name of the group you're looking for.

---

## 4. Study Mode

Study mode is the heart of StudyCards. It allows you to review your flashcards interactively and assess your knowledge level.

### 4.1 Starting a Study Session

**Steps:**

1. Select the **Study** tab in the navigation bar.
2. Find and select the group you want to study.
3. The first flashcard will appear on screen.

<img src="screenshots/ios/start_study.png" alt="Start Study" width="500">

<img src="screenshots/macos/start_study.png" alt="Start Study - macOS" width="500">

### 4.2 Navigating Between Cards

During a study session:

1. Read the **front** of the card (the question).
2. Think about the answer.
3. Tap **Show Answer** or tap the card to reveal the **back** (the answer).
4. Rate your knowledge with one of three buttons:

| Button | Meaning | Description |
|--------|---------|-------------|
| 🟢 **Easy** | You knew it well | The card will be marked as mastered. It will appear less frequently. |
| 🟡 **Unsure** | You remembered with difficulty | The card will reappear soon for reinforcement. |
| 🔴 **Didn't Know** | You didn't know it | The card will be repeated more times until you learn it. |

**Keyboard Shortcuts (macOS):**

| Key | Action |
|-----|--------|
| **Space** | Flip the card |
| **1** | Rate as Easy |
| **2** | Rate as Unsure |
| **3** | Rate as Didn't Know |

<img src="screenshots/ios/study_session.png" alt="Study Mode" width="500">

<img src="screenshots/macos/study_session.png" alt="Study Mode - macOS" width="500">

### 4.3 Completing a Study Session

When you've reviewed all cards in the group:

1. A completion summary will appear.
2. You'll see how many cards you rated as *Easy*, *Unsure*, and *Didn't Know*.
3. Tap **Study Again** to repeat or **Back to Groups** to exit.

<img src="screenshots/ios/study_summary.png" alt="Study Summary" width="500">

<img src="screenshots/macos/study_summary.png" alt="Study Summary - macOS" width="500">

---

## 5. Import and Export

StudyCards allows you to transfer flashcards between devices or create backups using CSV and JSON files.

### 5.1 Exporting Flashcards

**Steps:**

1. Open the group you want to export.
2. Tap the actions menu and select **Export**.
3. Select the export format:
   - **CSV:** Spreadsheet format. Ideal for opening in Excel, Numbers, etc. Does not include images.
   - **JSON:** Complete format. Includes text, LaTeX formulas, and base64 images.
4. Choose where to save the file (Files, iCloud Drive, etc.).

<img src="screenshots/ios/export.png" alt="Export" width="500">

<img src="screenshots/macos/export.png" alt="Export - macOS" width="500">

### 5.2 JSON File Structure

The exported JSON file has the following structure:

```json
{
  "groupName": "Spanish Vocabulary",
  "version": "1.0",
  "createdAt": "2026-07-12T10:30:00Z",
  "cards": [
    {
      "front": "What is the capital of France?",
      "back": "Paris.",
      "frontLatex": null,
      "backLatex": null,
      "difficulty": 0,
      "frontImage": "base64_encoded_string...",
      "backImage": null
    }
  ]
}
```

### 5.3 CSV File Structure

The CSV file uses the following columns:

```csv
front,back,frontLatex,backLatex,difficulty,frontImage,backImage
"What is the capital of France?","Paris.","","","0","",""
```

> **Note:** Images in CSV format are exported as base64 strings in the `frontImage` and `backImage` columns.

### 5.4 Importing Flashcards

**Steps:**

1. In the flashcard list of a group, tap the actions menu and select **Import**.
2. Select a CSV or JSON file from your device.
3. StudyCards will import the flashcards into the current group.

<img src="screenshots/ios/import.png" alt="Import" width="500">

<img src="screenshots/macos/import.png" alt="Import - macOS" width="500">

> **Note:** If you import a JSON file with base64 images, the images will be displayed correctly in the flashcards.

### 5.5 Common Import Errors

| Error | Cause | Solution |
|-------|-------|----------|
| *Format not recognized* | The file is not valid CSV or JSON | Verify the file has the correct extension and is not corrupted |
| *Empty file* | The file contains no cards | Check that the file has at least one row of data |

---

## 6. Sharing Flashcards

StudyCards makes it easy to share your flashcards with others.

### 6.1 Sharing a Group as JSON

**Steps:**

1. Open the group you want to share.
2. Tap the actions menu and select **Share**.
3. The system share sheet will open.
4. Choose the app or method to send:
   - **AirDrop** — for nearby Apple devices.
   - **Mail** — send the JSON file as an attachment.
   - **WhatsApp** — send the JSON file as a document.
   - **Messages** — send via iMessage.
   - **Other apps** — any app that accepts file attachments.

<img src="screenshots/ios/share.png" alt="Share" width="500">

<img src="screenshots/macos/share.png" alt="Share - macOS" width="500">

### 6.2 Receiving Shared Flashcards

When someone sends you a StudyCards JSON file:

1. Open the file on your device.
2. Select **Open in StudyCards** or **Import**.
3. The group will be automatically added to your collection.

---

## 7. Settings

Customize StudyCards to fit your preferences.

### 7.1 Appearance

Control the visual theme of the app.

| Option | Description |
|--------|-------------|
| **System** | Automatically match your device's appearance setting (light or dark). |
| **Light** | Always use light mode. |
| **Dark** | Always use dark mode. |

**Steps:**

1. Go to the **Settings** tab.
2. In the **Appearance** section, select one of the three options.
3. The change is applied immediately.

<img src="screenshots/ios/appearance.png" alt="Appearance Settings" width="500">

<img src="screenshots/macos/appearance.png" alt="Appearance Settings - macOS" width="500">

### 7.2 Language

StudyCards is available in 8 languages. You can force a specific language or use the system default.

| Language | Code |
|----------|------|
| **System** | Automatically selects the device language |
| Español | es |
| English | en |
| Português | pt |
| Français | fr |
| Deutsch | de |
| Italiano | it |
| 日本語 | ja |
| 中文 | zh |

**Steps:**

1. Go to the **Settings** tab.
2. In the **Language** section, select the desired language.
3. The change is applied immediately without restarting.

<img src="screenshots/ios/language.png" alt="Language Settings" width="500">

<img src="screenshots/macos/language.png" alt="Language Settings - macOS" width="500">

### 7.3 Study Order

Set the default order in which flashcards are shown during study mode.

| Option | Description |
|--------|-------------|
| **Sequential** | Cards are shown in creation order (or manual order if you've reordered). |
| **Random** | Cards are shuffled in each session. |

**Steps:**

1. Go to the **Settings** tab.
2. In the **Study Order** section, select your preference.
3. The change will apply to all future study sessions.

<img src="screenshots/ios/study_order.png" alt="Study Order Settings" width="500">

<img src="screenshots/macos/study_order.png" alt="Study Order Settings - macOS" width="500">

---

## 8. Tips

### Organization

- **Create a group for each subject or topic.** This will help you quickly find what you need to study.
- **Use clear, short names** for groups and flashcards. Avoid text that's too long to read on screen.
- **Manually reorder flashcards** to put the most important ones first.
- **Review your groups periodically.** Delete cards you've mastered and add new ones to match your progress.

### Study

- **Use spaced repetition.** Study the same cards on different days to consolidate long-term memory.
- **Don't ignore difficult cards.** If you rate a card as *Didn't Know*, study that group again soon.
- **Mix study modes.** Alternate between sequential and random order to avoid memorizing card positions.
- **Use keyboard shortcuts** on macOS to study faster (Space, 1, 2, 3).
- **Study in short sessions.** 10 to 20 minutes is enough for a productive session.

### Content

- **Write clear, concise questions.** Avoid ambiguity.
- **One idea per card.** Don't overload the front or back with too much information.
- **Use images.** A diagram or image can be more effective than a paragraph of text.
- **Use LaTeX formulas** for math or science content. They're precise and look professional.

### Backups

- **Export your groups regularly.** Save copies to iCloud Drive or your computer.
- **Use JSON format** if you want to preserve images. CSV only saves text.
- **Share your flashcards** with classmates or colleagues to collaborate on studying.

### Performance

- **Close other apps** when studying so StudyCards runs without interruptions.
- **Keep the app updated** for the latest features and bug fixes.
- **If LaTeX formulas don't render**, check your internet connection. MathJax needs to download resources the first time.

---

## Legal Information

- **StudyCards** is an independently developed application.
- MathJax usage is subject to its Apache 2.0 license.
- Your data is stored only on your device. StudyCards does not collect or share personal information.

---

*StudyCards User Manual — Version 1.1 — July 2026*

