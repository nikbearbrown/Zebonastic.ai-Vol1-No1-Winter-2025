# How to Create an EPUB and Kindle MOBI File from a Word Document Using Sigil (with AI Assistance)



#### **Introduction**

Publishing professional-quality ebooks can be a challenging task, especially when transitioning from a Word document to formats like EPUB or Kindle MOBI. This guide simplifies the process using the powerful combination of AI tools like ChatGPT or Claude, the document conversion tool Pandoc, and Sigil software for EPUB editing. 

By the end of this guide, you’ll have all the knowledge you need to create perfectly formatted ebooks ready for publication on platforms like Amazon Kindle. Let’s dive in!

---

#### **Initial Setup**

Start with a well-structured Word document. Proper formatting at this stage will save you a lot of trouble later:
- Use **Heading 1 (H1)** for main headings and **Normal style** for body text.
- Include additional formatting elements like links, images, bold, italics, and subheadings (**H2**, **H3**, etc.).
- Ensure consistency throughout the document.

---

#### **Challenges with Direct Upload to Kindle**

Uploading a Word document directly to Kindle Direct Publishing (KDP) often results in:
- Unwanted text colors.
- Bulleted lists in inconsistent font sizes.
- Overall formatting errors that detract from the professional appearance of the ebook.

To avoid these pitfalls, we’ll preprocess the document using AI and convert it to clean HTML before finalizing it in Sigil.

---

#### **Step 1: Using ChatGPT or Claude for Grammar and Spell Checking**

AI tools like ChatGPT or Claude can streamline the editing process:
1. **Upload the Document**: Open your Word document or Google Doc in an AI assistant.
2. **Grammar and Spell Check**: Request a comprehensive grammar and spell check to refine the content.
3. **Export to Markdown**: Once the content is polished, save it in Markdown format for further processing.

---

#### **Step 2: Converting Markdown to HTML with Pandoc**

Markdown is a clean, lightweight format that converts easily to HTML:
1. Install **Pandoc** (if not already installed).
2. Run the following command to convert your Markdown file to HTML:
   ```bash
   pandoc input.md -o output.html
   ```
3. The resulting HTML will be free of unnecessary Word-specific tags, ensuring a clean starting point for your EPUB.

4. **Validate the HTML**: Use Sigil’s validation tool or another validator to identify and fix any errors.

---

#### **Step 3: Adding Metadata and Table of Contents in Sigil**

1. **Open the HTML in Sigil**: Import the cleaned-up HTML file into Sigil.
2. **Add Metadata**: Include the book title and author in the metadata section.
3. **Generate Table of Contents**:
   - Use Sigil’s **"Generate Table of Contents"** feature to automatically create a TOC based on H1 headings.
   - Additionally, create an **HTML-based table of contents** to ensure it’s visible on Kindle devices.

---

#### **Step 4: Handling Images**

If your document includes images, follow these steps for optimal display:
1. **Reinsert Images in Sigil**: Use the "Insert File" button in Sigil to add images to your EPUB.
2. **Optimize Image Size**:
   - Keep images 500–600 pixels wide.
   - Ensure file sizes are under 127 KB.
3. **Apply CSS for Images**:
   ```css
   img {
     width: 100%;
   }
   ```
   This ensures images scale appropriately across devices.

---

#### **Step 5: Applying CSS and Stylesheets**

Create a stylesheet to maintain consistent formatting:
- Ensure new chapters (H1 headings) start on a new page:
  ```css
  h1 {
    page-break-before: always;
  }
  ```
- Include your styles in the HTML `<head>` section to ensure they render correctly.

---

#### **Step 6: Previewing and Converting**

Use **Amazon’s Kindle Previewer** to:
1. **Preview the EPUB**: Check how the ebook looks on various Kindle devices.
2. **Convert to MOBI**: Kindle Previewer automatically converts your EPUB file to MOBI format for publishing.

---

#### **Final Output**

The resulting MOBI file will include:
- Properly formatted text with consistent font sizes.
- Functional links and headings.
- New chapters starting on fresh pages.
- Images and other content displayed perfectly across devices.

---

#### **Conclusion**

By combining AI tools, Pandoc, and Sigil, you can produce polished, professional-quality ebooks without the headaches of manual HTML cleanup. This process ensures your content is formatted consistently and optimized for a seamless reading experience.

Embrace these tools and techniques to transform your Word documents into outstanding ebooks, ready to captivate your audience.

Happy publishing! 🚀
