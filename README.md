<!doctype html>
<html lang="hi">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>मीरा सुरेश सेवा न्यास — सेवा में समर्पित</title>
  <meta name="description" content="मीरा सुरेश सेवा न्यास, कसया, कुशीनगर — गरीबों की सेवा, बच्चों की शिक्षा और सांस्कृतिक संरक्षण। सदस्यता केवल ₹51 में।">
  <meta name="keywords" content="मीरा सुरेश सेवा न्यास, समाज सेवा, कुशीनगर, सदस्यता, गरीब बच्चों की पढ़ाई">
  <style>
    body{font-family:Arial,Helvetica,sans-serif;margin:0;color:#222;background:#f4f7f5}
    header{background:#1f7a3a;color:#fff;padding:20px 15px}
    .wrap{max-width:1000px;margin:18px auto;padding:16px;background:#fff;border-radius:8px;box-shadow:0 2px 8px rgba(0,0,0,0.06)}
    h1{margin:0;font-size:26px}
    p.lead{color:#333}
    .grid{display:grid;grid-template-columns:1fr;gap:14px}
    @media(min-width:800px){ .grid{grid-template-columns:1fr 320px} }
    .card{padding:14px;border-radius:8px;background:#fcfff9;border:1px solid #e6efe6}
    .btn{display:inline-block;padding:10px 14px;border-radius:6px;background:#2b8b44;color:#fff;border:none;cursor:pointer;text-decoration:none}
    .btn-ghost{background:#6b6b6b}
    footer{text-align:center;padding:14px;color:#666;font-size:14px}
    /* modal */
    .modal{display:none;position:fixed;inset:0;background:rgba(0,0,0,0.5);align-items:center;justify-content:center}
    .modal-box{background:#fff;padding:18px;border-radius:8px;max-width:560px;width:94%}
    .field{margin:8px 0;padding:10px;background:#f6fbf6;border-radius:6px;border:1px solid #e9f3ea}
    small.note{display:block;color:#444;margin-top:6px}
  </style>
</head>
<body>
  <header>
    <div class="wrap">
      <h1>मीरा सुरेश सेवा न्यास</h1>
      <div>वार्ड नं. 24, सुभाष नगर, कसया, कुशीनगर</div>
    </div>
  </header>

  <main class="wrap">
    <section class="grid">
      <div>
        <div class="card">
          <h2>हम क्या करते हैं</h2>
          <p class="lead">मीरा सुरेश सेवा न्यास गरीबों व जरूरतमंदों के कल्याण तथा हमारी संस्कृति के संरक्षण के लिए काम करती है। हम शिक्षा, स्वास्थ्य, महिला सशक्तिकरण और livelihood परियोजनाओं पर विशेष ध्यान देते हैं।</p>
        </div>

        <div class="card" style="margin-top:12px">
          <h3>गरीब बच्चों के लिए शिक्षा — हमारी पहल</h3>
          <p>हमारा उद्देश्य क्षेत्र के गरीब बच्चों को गुणवत्तापूर्ण शिक्षा, पुस्तकें, स्कॉलरशिप और ट्यूशन सहायता प्रदान करना है। आपकी सदस्यता और दान से हम पाठ्य सामग्री, स्कूल यूनिफॉर्म और डिजिटल शिक्षा समर्थन दे पाएँगे।</p>
          <ul>
            <li>स्कॉलरशिप और स्टेशनरी वितरण</li>
            <li>सप्ताहांत ट्यूशन और कोचिंग</li>
            <li>डिजिटल लर्निंग (मोबाइल/टैब सपोर्ट जहाँ संभव)</li>
          </ul>
          <p class="small"><strong>आप सहयोग कैसे कर सकते हैं:</strong> सदस्यता लें (₹51) या दान करें — सभी दान बच्चों की शिक्षा में प्रयुक्त होंगे।</p>
        </div>

        <div class="card" style="margin-top:12px">
          <h3>हमारे उद्देश्य</h3>
          <ol>
            <li>गरीबों के लिए सहायता और कल्याणकारी कार्यक्रम</li>
            <li>स्थानीय संस्कृति और परम्परा का संरक्षण</li>
            <li>महिला सशक्तिकरण एवं आजीविका प्रशिक्षण</li>
            <li>औषधीय पौधों का संवर्धन और पर्यावरण सुरक्षा</li>
          </ol>
        </div>
      </div>

      <aside>
        <div class="card">
          <h3>सदस्यता — केवल ₹51</h3>
          <p>हमारे मिशन का हिस्सा बनने के लिए सदस्यता लें।</p>
          <button class="btn" onclick="openModal()">सदस्यता लें — ₹51</button>
        </div>

        <div class="card" style="margin-top:12px">
          <h3>संपर्क</h3>
          <p>मीरा सुरेश सेवा न्यास<br>वार्ड नं. 24, सुभाष नगर, कसया, कुशीनगर</p>
          <p>फोन: 9838011426</p>
        </div>
      </aside>
    </section>
  </main>

  <div id="modal" class="modal" onclick="if(event.target==this) closeModal()">
    <div class="modal-box">
      <h3>सदस्यता भुगतान — ₹51</h3>
      <p>नीचे बैंक विवरण पेमेंट करने हेतु हैं। भुगतान के बाद कृपया स्क्रीनशॉट व नाम/फोन नंबर हमें भेजें (9838011426) ताकि सदस्यता कन्फर्म की जा सके।</p>

      <div class="field"><strong>बैंक का नाम:</strong><div>State Bank of India (ADB Kasia)</div></div>
      <div class="field"><strong>IFSC:</strong><div id="ifsc">SBIN0005955</div></div>
      <div class="field"><strong>खाता संख्या:</strong><div id="acc"><em>&lt;ACCOUNT_NUMBER_HERE&gt;</em></div></div>
      <div class="field"><strong>प्राप्तकर्ता नाम:</strong><div>मीरा सुरेश सेवा न्यास</div></div>

      <small class="note">सरल विकल्प: यदि आप चाहें तो हम SBI Collect या Razorpay के माध्यम से एक सीधा पेमेंट लिंक बनवाने में मदद कर देंगे — उसके बाद लोग एक क्लिक में ₹51 दे पाएँगे।</small>

      <div style="margin-top:12px;text-align:right">
        <button class="btn btn-ghost" onclick="closeModal()">बंद करें</button>
      </div>
    </div>
  </div>

  <footer>
    © <span id="yr"></span> मीरा सुरेश सेवा न्यास — सेवा और शिक्षा के लिए समर्पित
  </footer>

  <script>
    document.getElementById('yr').innerText = new Date().getFullYear();
    function openModal(){ document.getElementById('modal').style.display='flex'; }
    function closeModal(){ document.getElementById('modal').style.display='none'; }
  </script>
</body>
</html>
