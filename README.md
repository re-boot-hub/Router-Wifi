# Hotspot-wifi-Gui
ITA: Interfaccia GUI per creare e gestire una rete wifi locale dal PC (Windows) <br>
ING: GUI interface to create and manage a local wifi network from the PC (Windows) <br>

Link Ide (Dev-C++): https://sourceforge.net/projects/embarcadero-devcpp/files/v6.0/ <br>
Link off wifi: https://technitium.com/tmac/

<H1>  Attenzione / Warning </H1>
Il programma funziona solo con schede di rete che supportano la monitor mode. <br>
Se volete usare una scheda di rete secondaria dovete disattivare la scheda di rete primaria con Tmac (Link off wifi) <br><br>

The program works only with network adapters that support monitor mode <br>
If you want to use a secondary network card you have to disable the primary network card with Tmac (Link off wifi) <br> <br>

<H1>  Aggiornamenti futuri / Future updates </H1><br>

ITA
1. Implementazione GUI wxWidgets-3.2.1 <br>
2. estendere il WiFi in ingresso (Ripetitore WiFi) <br>
Esempio


<a href="https://www.amazon.it/TP-Link-RE190-Ripetitore-Wireless-Compatibile/dp/B081HFWWSV?__mk_it_IT=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=15C6SJ4H3OENK&keywords=ripetitore&qid=1666522719&qu=eyJxc2MiOiI0LjAyIiwicXNhIjoiMy44NiIsInFzcCI6IjMuMTMifQ%3D%3D&sprefix=ripetitor%2Caps%2C309&sr=8-6&linkCode=ll1&tag=12345678054cd-21&linkId=7e90abe8e5c30a40a6ee19f33e9ea4c4&ref_=as_li_ss_tl" target="blank">
 <?xml version="1.0" encoding="iso-8859-1"?>
 <!-- Generator: Adobe Illustrator 19.0.0, SVG Export Plug-In . SVG Version: 6.00 Build 0)  -->
 <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
   viewBox="0 0 487.875 487.875" style="enable-background:new 0 0 487.875 487.875; fill: white" xml:space="preserve">
 <g>
  <g>
   <path d="M262.503,320.275c-5.5-8.5-22.4-16.3-35.4,0l-83.3,136.4c-5.3,8.5-1.2,31.2,17.7,31.2h166.6c11.9,0,28-13.9,16.7-33.3
    L262.503,320.275z M197.903,447.275l46.9-77.1l46.9,77.1H197.903z"/>
   <path d="M436.403,76.575c-106.3-102.1-279.1-102.1-385.3,0c-7.3,8.3-8.3,20.8,0,29.2c8.3,7.3,20.8,8.3,29.2,0
    c89.6-87.5,237.4-87.5,328,0c4.2,3.1,16.5,9.6,28.1,0C444.703,97.375,444.703,84.875,436.403,76.575z"/>
   <path d="M129.203,143.175c-7.3,8.3-8.3,20.8,0,29.2c8.3,7.3,20.8,8.3,29.2,0c47.9-45.8,125-45.8,171.8,0c4.2,3.1,15.9,9.9,27.1,0
    c8.3-8.3,8.3-20.8,0-29.2C294.703,82.775,191.603,82.775,129.203,143.175z"/>
   <path d="M222.903,243.175c11.5-11.5,31.2-11.5,42.7,0c12.6,9.8,25,4.3,28.1,0c8.3-8.3,8.3-20.8,0-29.2c-28.1-26-72.9-26-100,0
    c-7.3,8.3-8.3,20.8,0,29.2C202.103,250.475,214.503,250.475,222.903,243.175z"/>
  </g>
 </g>
 </svg>
</a>
 
<br><br>

ENG
1. GUI implementation with wxWidgets-3.2.1
2. Extend incoming WiFi (WiFi Repeater) <br>
E.X.

<a href="https://www.amazon.it/TP-Link-RE190-Ripetitore-Wireless-Compatibile/dp/B081HFWWSV?__mk_it_IT=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=15C6SJ4H3OENK&keywords=ripetitore&qid=1666522719&qu=eyJxc2MiOiI0LjAyIiwicXNhIjoiMy44NiIsInFzcCI6IjMuMTMifQ%3D%3D&sprefix=ripetitor%2Caps%2C309&sr=8-6&linkCode=ll1&tag=12345678054cd-21&linkId=7e90abe8e5c30a40a6ee19f33e9ea4c4&ref_=as_li_ss_tl" target="blank">
 <?xml version="1.0" encoding="iso-8859-1"?>
 <!-- Generator: Adobe Illustrator 19.0.0, SVG Export Plug-In . SVG Version: 6.00 Build 0)  -->
 <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
   viewBox="0 0 487.875 487.875" style="enable-background:new 0 0 487.875 487.875; fill: white" xml:space="preserve">
 <g>
  <g>
   <path d="M262.503,320.275c-5.5-8.5-22.4-16.3-35.4,0l-83.3,136.4c-5.3,8.5-1.2,31.2,17.7,31.2h166.6c11.9,0,28-13.9,16.7-33.3
    L262.503,320.275z M197.903,447.275l46.9-77.1l46.9,77.1H197.903z"/>
   <path d="M436.403,76.575c-106.3-102.1-279.1-102.1-385.3,0c-7.3,8.3-8.3,20.8,0,29.2c8.3,7.3,20.8,8.3,29.2,0
    c89.6-87.5,237.4-87.5,328,0c4.2,3.1,16.5,9.6,28.1,0C444.703,97.375,444.703,84.875,436.403,76.575z"/>
   <path d="M129.203,143.175c-7.3,8.3-8.3,20.8,0,29.2c8.3,7.3,20.8,8.3,29.2,0c47.9-45.8,125-45.8,171.8,0c4.2,3.1,15.9,9.9,27.1,0
    c8.3-8.3,8.3-20.8,0-29.2C294.703,82.775,191.603,82.775,129.203,143.175z"/>
   <path d="M222.903,243.175c11.5-11.5,31.2-11.5,42.7,0c12.6,9.8,25,4.3,28.1,0c8.3-8.3,8.3-20.8,0-29.2c-28.1-26-72.9-26-100,0
    c-7.3,8.3-8.3,20.8,0,29.2C202.103,250.475,214.503,250.475,222.903,243.175z"/>
  </g>
 </g>
 </svg>
</a>

 
<h1>  Immagini / Images </h1> <br>

![](https://1.bp.blogspot.com/-a58Y44mHLos/YM5M7w2T3qI/AAAAAAAAAkk/vlfZYD2EzysaPR1T6PUaMTCes4T_CngBwCLcBGAsYHQ/s394/Desktop_wifi_wifi-gui.png)
