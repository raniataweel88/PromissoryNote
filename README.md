<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" herf="styleREADME.css">
</head>
<body>

<h1>📄 Promissory Note Generator (PDF)</h1>

<p class="center">A professional promissory note generator that creates ready-to-print PDF documents based on debtor information, guarantor details, the amount, payment method, and the number of notes. It supports Arabic fonts, generates multiple notes per page, and allows direct printing.</p>

<h2>🚀 Features</h2>
<ul>
  <li>Generate ready-to-print PDF promissory notes</li>
  <li>Create multiple notes at once</li>
  <li>Automatic <strong>+1 month</strong> increment for each note's due date</li>
  <li>Arabic font support (Amiri) inside PDF</li>
  <li>Automatically opens the print window</li>
  <li>Uses a background template image</li>
  <li>Auto serial numbering (1/5, 2/5, 3/5 …)</li>
</ul>

<h2>🛠️ Technologies Used</h2>
<ul>
  <li>JavaScript</li>
  <li>jsPDF</li>
  <li>SweetAlert2</li>
  <li>HTML & CSS</li>
  <li>Amiri Arabic Font (Base64)</li>
  <li>JPEG Template Image</li>
</ul>

<h2>📂 How to Run the Project</h2>
<h3>1️⃣ Clone the repository</h3>
<pre><code>git clone https://github.com/raniataweel88/PromissoryNote.git</code></pre>

<h3>2️⃣ Open the project folder</h3>
<p>Open the folder using VS Code or any text editor.</p>

<h3>3️⃣ Run the project</h3>
<p>Open the file <code>index.html</code> in your browser.</p>

<h2>🔗 Live Demo</h2>
<p class="center">See the running version here: <a href="https://promissorynote.netlify.app/" target="_blank">https://promissorynote.netlify.app/</a></p>

<h2>🧩 How to Use</h2>
<ul>
  <li>Enter debtor and guarantor information</li>
  <li>Enter the amount in Dinar and Fils</li>
  <li>Enter the issue date</li>
  <li>Enter the due date</li>
  <li>Select the number of promissory notes</li>
  <li>Click <strong>Generate</strong> to create the PDF</li>
</ul>

<h2>📅 Due Date Auto-Increment Example</h2>
<p>If the original due date is <code>27/01/2025</code> and you select <strong>5 notes</strong>, the system will generate the following due dates:</p>

<table>
  <tr>
    <th>Note Number</th>
    <th>Due Date</th>
  </tr>
  <tr><td>1</td><td>27/01/2025</td></tr>
  <tr><td>2</td><td>27/02/2025</td></tr>
  <tr><td>3</td><td>27/03/2025</td></tr>
  <tr><td>4</td><td>27/04/2025</td></tr>
  <tr><td>5</td><td>27/05/2025</td></tr>
</table>

<h2>📁 Project Structure</h2>
<pre><code>
PromissoryNote/
│── index.html
│── script.js
│── style.css
│── template.jpg
│── amiriFontBase64.js
│── README.html
</code></pre>

<h2>📜 License</h2>
<p>This project is free and open-source.</p>

<h2>👩‍💻 Developer</h2>
<p class="center"><strong>Rania Taweel</strong></p>

<h2>⭐ Support the Project</h2>
<p class="center">If you like this project, please give it a <a href="https://github.com/raniataweel88/PromissoryNote" target="_blank">⭐ on GitHub</a>!</p>

</body>
</html>
