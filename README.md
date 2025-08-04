Resume Builder
This is a simple, interactive resume builder created using a single HTML file with Tailwind CSS for styling and vanilla JavaScript for functionality. It allows users to easily edit their personal information, education, experience, and other sections in a form and see a live preview of their resume. The final resume can be downloaded as a PDF or DOCX document.

Features
Live Preview: As you type in the form fields, the resume preview on the right updates in real-time.

Customizable Sections: Easily add, remove, and edit entries for Education, Experience, Publications, Projects, Skills, Certifications, and References.

Download as PDF: Generate a professional-looking PDF of your resume with a single click.

Download as DOCX: Generate a downloadable Word document (DOCX) of your resume.

Responsive Design: The layout is designed to be user-friendly on both desktop and mobile devices.

How to Use
Fill out the Form: On the left side of the page, you'll find a form with various sections. Fill in your personal details, education, work experience, and other relevant information.

Use "Add" Buttons: For sections like Education, Experience, and Publications, use the "Add" button to add more entries.

Check the Preview: The right side of the page shows a live preview of how your resume will look.

Download: When you are satisfied with the content, click the "Download PDF" or "Download DOCX" buttons at the bottom of the page to save your resume.

Customization
The code is self-contained in a single HTML file, making it easy to customize.

Fonts: You can change the fonts by editing the <style> section in the <head> of the HTML file. The current fonts are 'Palatino Linotype' for headings and 'Calibri' for body text.

Colors and Styling: All styling is handled with Tailwind CSS classes. You can modify these classes to change colors, spacing, and layout.

New Sections: You can add new sections by creating a new <div> in the form and a corresponding section in the resume preview. You will also need to update the JavaScript to handle the new fields.

Technologies Used
HTML: For the structure of the document.

Tailwind CSS: A utility-first CSS framework for rapid styling.

JavaScript: For handling form inputs, live updates, and download functionality.

html2pdf.js: A third-party library used to generate the PDF download.

docx: A third-party library used to generate the DOCX download.

Feel free to modify and adapt this resume builder to your needs!
