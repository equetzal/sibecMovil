---


---

<h1 id="sibec-móvil">SIBec Móvil</h1>
<p>The Mobile Scholarship Information System of the National Polytechnic Institute, it’s an android application that facilitates and allows students to access all their information related to the scholarships they have, want or had.</p>
<h2 id="what-does-it-do">What does it do?</h2>
<h2 id="how-was-it-designed">How was it designed?</h2>
<p>Cards. The entire app is based on flexible and responsive cards, adaptable to all types of screens and resolutions. Due to their design, tap is the first intuitive action to perform with them, so they are made to dynamically change all the actions to be performed.</p>
<h3 id="techs">Techs</h3>
<dl>
<dt>UI/UX</dt>
<dd>For the User Experience and User Interface, the Adobe XD and Illustrator tools were used to create the concept of the app.Also the new <em>androidx</em> namespace library was used on all the resources of the android project.</dd>
<dt>App</dt>
<dd>For the development of the app, Android Studio was the selected IDE for using the Android SDK; Kotlin is the main programming language in order to keep the application up to date with Google’s development guidelines</dd>
<dt>Content</dt>
<dd>All the content is based on a SOAP webservice that provides to the app all the student information</dd>
<dt>Notifications</dt>
<dd>Firebase Cloud Messaging services, was the Push-Notifications service provider selected by it’s interoperability with the SIBec servers.</dd>
</dl>
<h3 id="features">Features</h3>
<dl>
<dt>Dynamic Cards</dt>
<dd>One of the main features are the dynamic cards, since they are everywhere, and they have all kinds of modifiable features, such as titles, subtitles, descriptions, text colors, a whole library of available icons, gradient colors and customizable links ranging from opening a url, a screen within the app, showing a warning or even opening a location on the map. Everything described in a simple json that is received from a web service, which means that practically all the content can be changed without having to launch constant updates.</dd>
<dt>Flexible Dialogs</dt>
<dd>Dialogues are one of the main parts of an application, as they focus all the user’s attention on important content. Regularly, a dialogue is usually tailored to show something very specific. But flexible dialogues describe all content from one server. From an important notice, to an update or deposit message. Everything is customizable.</dd>
<dt>Point-to-point encryption</dt>
<dd>When talking about bank details, the information is very valuable. We know that the content that is saved by SIBec can be very delicate, and that is why all communication is encrypted to protect it from any entity that wants to intercept such data.</dd>
<dt>Data Modules</dt>
<dd>Using kotlin and a fully object-oriented model, working with a local database such as SQLite, becomes an impractical option, therefore, the Gson library was used to store all the application data in encrypted form. To achieve this, a data module was implemented using generics templates, one of the best features of Kotlin; This module is capable of working with any type of data, serializing it, encrypting it, storing it and making availability queries, updating data and deleting data from any application activity.</dd>
<dt>Dark Mode</dt>
<dd>Nowadays, it is very common to think about the brightness of interfaces based on light colors and how difficult it is to deal with them at night. That is why, from the beginning of development, dark mode was implemented, to change the predominant colors of the app to more comfortable ones for the view.</dd>
<dt>Filtering versions</dt>
<dd>Being a system that deals with sensitive data, finding a vulnerability can be very risky. That is why there is a version blocking system, in which it is possible to verify the version of the app that sends all requests and block its use entirely from the SIBec servers. In this way, we can seal any risk due to a vulnerability while the development team can solve the problem.</dd>
<dt>Notifications</dt>
<dd>Notifications is one of the main axes that motivated the creation of the SIBec Móvil despite the current existence of the SIBec Web. The main objective is to make known to all students information about scholarship calls, the status of their deposits as well as to send a direct message to any student who needs to pay special attention to their scholarship situation.</dd>
</dl>
<h2 id="developers">Developers</h2>
<p>The system is divided into two main sectors, the mobile application, and the APIs that connect the SIBec servers to the app.</p>
<dl>
<dt><a href="https://github.com/neooku">Patricia Benitez</a></dt>
<dd>She is the main developer of the APIs that attend to all the requests of the app. The web services were developed in SOAP, using Java as the language for the backend and making the queries in an Oracle SQL database.</dd>
<dt><a href="https://github.com/equetzal">Enya Quetzalli</a></dt>
<dd>She is the main developer of the mobile application, it uses Kotlin as the main development language for the Android SDK, in addition to using Adobe XD for the layout of the application and Adobe Illustrator for all the graphic content of the system.</dd>
<dt><a href="https://github.com/HansDeveloper">Hans González</a></dt>
<dd>He was the initial developer of the application, who due to his short time in the project, could not make large contributions in code, but he did lay the foundations for the entire project, as well as its use cases, the functions to be developed and the characteristics to implement.</dd>
</dl>
<h2 id="check-the-app-by-yourself">Check the app by yourself</h2>
<h2 id="disclaimer">Disclaimer</h2>
<p>This application has the authorship and intellectual property in the name of Enya Quetzalli Gómez Rodríguez, but all the rights of use, change, modification, distribution and ownership are from the National Polytechnic Institute.</p>
<p>Given the agreements given by the National Polytechnic Institute, it is not possible for me to make public any code that could put the use of the application at risk, as well as making visible any code that can be found to find any vulnerability in the system. However, I am working on a parallel project for free use in which everyone can use the resources created in this app, as well as create their own web services that will give the app a working start.</p>
<p>If you have any questions about the development of the app, or there are some features that you would like to implement on your own, or simply like guidance on development of any kind related to the app, do not hesitate to email me at <a href="mailto:egomezr1300@alumno.ipn.mx">egomezr1300@alumno.ipn.mx</a></p>

