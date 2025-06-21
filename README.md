<h2>🗓️ Serverless Appointment Booking App</h2>

<h3>🔍 Overview</h3>
<p>
  The <strong>Serverless Appointment Booking App</strong> is a fully functional, serverless web application that allows users to view available slots, book appointments, and make secure payments online.
  Built with <strong>Firebase, GCP, HTML, CSS, JavaScript</strong>, and <strong>Razorpay/Stripe</strong> payment integration.
</p>

<h3>💡 Features</h3>
<ul>
  <li>📆 Real-time appointment slot availability (Firestore)</li>
  <li>🔐 Firebase Authentication (Email/Google Login)</li>
  <li>💳 Razorpay/Stripe Payment Integration</li>
  <li>☁️ Firebase Cloud Functions (No backend server required)</li>
  <li>📤 Email confirmations on successful booking</li>
  <li>🧾 Booking history and payment logs</li>
</ul>

<h3>🧩 Tech Stack</h3>
<table>
  <tr><th>Layer</th><th>Technology</th></tr>
  <tr><td>Frontend</td><td>HTML, CSS, JavaScript</td></tr>
  <tr><td>Authentication</td><td>Firebase Auth</td></tr>
  <tr><td>Database</td><td>Firebase Firestore</td></tr>
  <tr><td>Backend</td><td>Firebase Cloud Functions (Node.js)</td></tr>
  <tr><td>Hosting</td><td>Firebase Hosting</td></tr>
  <tr><td>Payment</td><td>Razorpay / Stripe</td></tr>
</table>

<h3>📂 Folder Structure</h3>
<pre>
/appointment-app
├── /public         (Frontend files)
│   ├── index.html
│   ├── style.css
│   └── script.js
├── /functions      (Firebase cloud functions)
│   └── index.js
├── firebase.json
└── README.md
</pre>

<h3>🖥️ Sample Booking Form (index.html)</h3>
<pre>
&lt;form id="bookingForm"&gt;
  &lt;label&gt;Name:&lt;/label&gt;&lt;br&gt;
  &lt;input type="text" id="name" required&gt;&lt;br&gt;&lt;br&gt;

  &lt;label&gt;Email:&lt;/label&gt;&lt;br&gt;
  &lt;input type="email" id="email" required&gt;&lt;br&gt;&lt;br&gt;

  &lt;label&gt;Choose Slot:&lt;/label&gt;&lt;br&gt;
  &lt;select id="slot"&gt;
    &lt;option value="10AM"&gt;10:00 AM&lt;/option&gt;
    &lt;option value="11AM"&gt;11:00 AM&lt;/option&gt;
    &lt;option value="12PM"&gt;12:00 PM&lt;/option&gt;
  &lt;/select&gt;&lt;br&gt;&lt;br&gt;

  &lt;button type="submit"&gt;Proceed to Pay&lt;/button&gt;
&lt;/form&gt;
</pre>

<h3>✅ How It Works</h3>
<ol>
  <li>User visits the site and selects a time slot.</li>
  <li>Logs in via Firebase Authentication.</li>
  <li>Completes the payment through Razorpay/Stripe.</li>
  <li>Booking data is stored securely in Firestore.</li>
  <li>User receives a confirmation message/email.</li>
</ol>

