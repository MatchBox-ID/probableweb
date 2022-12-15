# probableweb
Probableweb adalah system whatsap web yang terhubung dengan server untuk bot whatsapp

# tutorial
Probableweb lebih simple digunakan daripada menggunakan system baileys yang sulit, probableweb lebih menggunakan kode yang singkat dan mudah dipahami

# konfigurasi
Secara detail probableweb menggunakan situs dns.safari yang menggunakan hosting, kami menggunakan firefall dns 1.1.1.1 yang canggih

# pesan media
``` ts
import makeWabot ${media-messages.js}
//media-message
type:"media-message.probableweb",
media:"https://github.com/matchbox-id.png",
{
  send.message:${is.contact-reply}
  send.media-buttonMessage:${is.contact-reply}
}
const [buttonjs]
textBot:"Halo Kak ${pushname} ini cuman pesan contoh yah",
footerTeks:"Example Message",
buttonId1:"github", text:"${prefix}github",
buttonId2:"owner", text:"${prefix}owner"
```
# pesan button lainnya
``` ts
import makeWabot ${button.mesages.js}
//button message
type:"button-more.probableweb",
button:"button, list-menu, urlButton"
{
  send.message:${is.contact-reply}
  send.allButton:${is.contact-reply}
}
const [buttonjs]
textBot:"halo kak ${pushname} ini cuman pesan contoh",
footerTeks:"Example Message",
buttonId1:"github", text:"${prefix}github}",
buttonId2:"owner", text:"${prefix}owner}"
{
}
const [list-menujs]
textBot:"Pilih List Menu Berikut",
footerTeks:"Example Message"
const sections = [
    {
	title: "Section 1",
	rows: [
	    {title: "Option 1", rowId: "option1"},
	    {title: "Option 2", rowId: "option2", description: "This is a description"}
	]
    },
   {
	title: "Section 2",
	rows: [
	    {title: "Option 3", rowId: "option3"},
	    {title: "Option 4", rowId: "option4", description: "This is a description V2"}
	]
    },
]
```
