# Freshbazarservices
Pest control and safety equipment supplier

<!DOCTYPE html>
<html>
<head>
<title>Freshbazar Services | Pest Control</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body { font-family: Arial; background:#f4f4f4; padding:20px; }
.box { background:#fff; padding:20px; max-width:500px; margin:auto; border-radius:8px; }
.call { background:green; color:white; padding:12px; text-align:center; margin:10px 0; }
input, select, button { width:100%; padding:10px; margin-top:10px; }
button { background:orange; border:none; font-size:16px; }
</style>
</head>

<body>
<div class="box">
<h2>FRESHBAZAR SERVICES</h2>
<p>Professional Pest Control Solutions</p>

<div class="call">
📞 <a href="tel:9590551453" style="color:white;">9590551453</a> |
<a href="tel:9585612677" style="color:white;">9585612677</a>
</div>

<form onsubmit="sendWhatsApp(); return false;">
<input id="name" placeholder="Your Name" required>
<input id="mobile" placeholder="Mobile Number" required>

<select id="pest" required>
<option value="">Select Pest Type</option>
<option>Cockroach Control</option>
<option>Bed Bug Control</option>
<option>Termite Control</option>
<option>Mosquito Control</option>
<option>Rodent Control</option>
</select>

<button type="submit">Send Enquiry via WhatsApp</button>
</form>
</div>

<script>
function sendWhatsApp() {
 let name = document.getElementById("name").value;
 let mobile = document.getElementById("mobile").value;
 let pest = document.getElementById("pest").value;

 let msg = `New Enquiry - Freshbazar Services
Name: ${name}
Mobile: ${mobile}
Pest: ${pest}`;

 let url = "https://wa.me/919590551453?text=" + encodeURIComponent(msg);
 window.open(url, "_blank");
}
</script>
</body>
</html>

