document.getElementById("downloadForm").addEventListener("submit", function(e) {
    e.preventDefault();
    let url = document.getElementById("url").value;

    // تنبيه بسيط - مكان إضافة كود التحميل الفعلي لاحقًا
    document.getElementById("result").innerHTML = `
        <p>سيتم معالجة رابطك: <b>${url}</b></p>
        <p>⚠ هذه نسخة تجريبية - أضف سكريبت التحميل لاحقاً</p>
    `;
});