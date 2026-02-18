<br>📌 Event Report generation <br> [2025]
    <br>A Tkinter-based desktop application that allows users to manage events, store event details , and generate event reports in Word format using docxtpl.<br>

<br>🛠 Features<br>
  ✅ Add New Events – Store event details in a local database.<br>
  ✅ View Saved Events – Display stored events in a structured format.<br>
  ✅ Upload Images – Attach event-related images.<br>
  ✅ Generate Event Report – Export event details into a formatted Word document (.docx).<br>
  ✅ User-Friendly UI – Built with Tkinter and ttk Notebook.<br>

🏗️ Tech Stack<br>
  Python – Core logic<br>
  Tkinter – GUI framework<br>
  docxtpl – Generate Word reports<br>
  ttk Notebook – Tabbed UI<br>
  json file - to store data 

📜 Usage<br>
  1️⃣ Open the application.<br>
  2️⃣ Fill in event details and click "Add Event".<br>
  3️⃣ Upload an image if needed.<br>
  4️⃣ View saved events under the "View Events" tab.<br>
  5️⃣ Generate a report using the "Export Report" tab.<br>

📄 Word Report Template (event_template.docx)<br>
      Your report will be generated using this format:<br>
          example- Event Name = {{ event.event_name }}<br>
📌 Ensure event_template.docx is present in the same folder!<br>
