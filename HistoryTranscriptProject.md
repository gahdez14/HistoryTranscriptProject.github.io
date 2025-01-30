---
layout: project
type: project
image: img/handwriting1.jpg
title: "ICS 496 Capstone - Training AI models to Read 19th Century Archival Documents"
date: 2025
published: true
labels:
  - AI
summary: "We will be training AI models to transcribe handwritten documents"
---

<img class="img-fluid" src="img/ICSLOGO.png">

# Training AI Models to Read 19th Century Archival Documents

## Purpose

<p>The goal of our project is to utilize Artificial Intelligence and Machine Learning to accurately transcribe historical, handwritten documents.  The timeline of our project will include determining which tools and approach will best achieve this goal.

</p>

## Week 1

<p>
For our initial meeting and consultation the project sponsor, we worked to solidify the scope of work that was to be accomplished.  
<br>
There were many questions that would have to be answered before we could fully determine the scope of work, and whether that work would be achievable within our timeline.  Despite what would seem like an easy task, there were many questions that needed to be answered:

<ul>
  <li>Are there legal implications for uploading archival documents onto open or subscription AI transcribing services?</li>
  <li>Would the Artificial Intelligence models be easier to train down to a specific author?  Or would the models be better suited for covering the vernacular and styles of a given time period?</li>
  <li>What products are out there currently that can best achieve our goal?</li>
</ul>

At the end of our first week, we would have to answer many questions to hopefully narrow down the scope and feasibility of our project.

</p>


## Week 2

<p>For the second week, we dove into the research of several applications and how they could be useful in accomplishing our goal.  One example is Transkribus, which is a popular platform for transcribing archival documents from photos.

*** Of note, transcribing is the act of turning audio or video into type.  Technically, the term for converting cursive handwriting to type text is referred to as “translating.”  Due to how awkward that sounds, we will stick to using the term “transcribing” to define the conversion of handwritten cursive into typed text.  ***
</p>

<h3>Transkribus</h3>

<p>
Transkribus.org is one of the front-running apps used for transcribing documents from handwriting to searchable typed text.  One of our tasks was to first understand and present the legal and privacy rules that the app operates under.  The goal of this is to ensure that there are no hidden agendas or nefarious uses of the data that is being uploaded to the application’s servers.
</p>

<p>
The Transkribus project operates as a CO-OP.  The statues of that CO-OP describe their mission statement but make no mention of the legal ownership or use of the documents that are uploaded.  There are operational processes, member rights, and cooperative functions that are mentioned.  This document specifically does not mention the Intellectual Property rights over the data or documents uploaded to their system.
<br>
The next document reviewed was the Privacy Policy.  The Privacy Policy does describe how the data is handled and stored.  Namely:
	<ol>
		<li>READ-COOP collects data transferred to Transkribus, including uploaded images, recognized text, ground truth data, trained recognition models, and metadata. </li>
		<li>The data is hosted on servers in Germany and Austria. </li>
		<li>Users maintain control over the data they upload. The policy states that the data must not contain Personal Data unless the user signs a Data Processing Addendum. </li>
		<li> Uploaded data is temporarily stored only for the duration necessary to complete text recognition and is deleted promptly thereafter. </li>
	</ol>
These are important points that we will make known to the sponsor and may determine the direction in which the data (or what data specifically) is processed.
</p>

<p>
Finally, the General Terms and Conditions more expressly document the relationship between user and platform and we surmise the following bullet points:
	<ol>
		<li>READ-COOP stores uploaded material only to the extent necessary to provide its services and improve its products. The platform does not guarantee permanent storage unless otherwise agreed upon.</li>
		<li>Documents submitted via Transkribus or APIs are stored only temporarily for processing purposes. For APIs, uploaded data is automatically deleted shortly after processing is completed.</li>
		<li>Ownership: Users retain ownership of all uploaded content, including handwritten material, processed results, and training data.</li>
		<li>Licensing: Users grant READ-COOP a limited, non-exclusive, worldwide, royalty-free license to store, modify, and process user content for the sole purpose of providing and improving its services.	</li>
		<li>Users maintain all intellectual property rights for their material and processed outputs unless explicitly stated otherwise.</li>
		<li>The policy explicitly states that "User Content remains yours," reaffirming user ownership over scanned and uploaded documents.</li>
		<li>Users can share custom-trained models with others via the platform, with two sharing options:
			<br>o	With Training Data- Makes both the model and the underlying training data public.
			<br>o	Without Training Data- Only the model is shared, and the training data is kept private.</li>
		<li>Users can withdraw consent for sharing at any time.</li>
	</ol>
</p>

<h3>Handwriting OCR</h3>
<p>
Another AI transcript app that we found during our research is <a href="https://www.handwritingocr.com/">Handwriting OCR</a>.
</p>

<p>
According to their website frequently asked questions page, "Handwriting OCR is a document automation service that specialises in digitizing documents containing handwriting. It uses a form of Optical Character Recognition (OCR) developed especially for reading handwriting <a href="#sources">(Source)</a>." 
</p>

<p>
Highlights about Handwriting OCR:
	<ol>
		<li>Supports a wide range of file formats such as PDF, JPG, PNG, GIFT, HEIC, and TIFF.</li>
		<li>Supports multiple languages for processing documents.</li>
		<li>AI Models are pre-trained on a diverse set of public domain and licensed datasets to ensure privacy and confidentiality of user data.</li>
		<li>Handwriting OCR has a comprehensive API that allows users to integrate their services directly into applications.</li>
	</ol>
</p>

<p>
In terms of the legal and privacy rules that Handwriting OCR operates under, here are some key points we found during our research <a href="#sources">(Source)</a>:
	<ol>
		<li>Handwriting OCR have explicitly stated that any information uploaded to their services belongs to the users and that they only use the user's uploaded data to deliver their OCR services. </li>
		<li>Users have full control over and data that is uploaded to their services. Users are able to delete data at any time. Handwriting OCR will automatically delete processed documents after 7 days by default but if the user wants to either shorten or lengthen the time data is deleted after processing, they are able to adjust that as well. Once data is deleted, it is immediately and permanently removed from Handwriting OCR systems.</li>
		<li>Handwriting OCR will only retain user uploaded data as long as necessary to provide their services, emphasizing that users can delete their data at any time.</li>
		<li>Any data that is in transit and stored uses industry-standard encryption, implementing rigorous access controls and security protocols. Any non-EU customer data is stored in the US.</li>
		<li>Handwriting OCR is also in compliance with several data protection standards and regulations such as GDPR (General Data Protection Regulation) and HIPAA (Health Insurance Portability and Accountability Act).</li>
		<li>If a user requests support regarding any of their documents and grants Handwriting OCR permission to view and access their documents, only then will Handwriting OCR view and access a users documents.</li>
	</ol>
</p>

### Sources
<ul>

<li>Privacy policy.  08 November 2024.  https://legal.transkribus.org/privacy</li>

<li>“Statutes of the READ-COOP SCE with limited liability.”2022.  Accessed 27 January 2025. https://help.transkribus.org/hubfs/Statutes_READ_COOP_SCE_current.pdf </li>

<li>General Terms and Conditions.  2024. Accessed: 27 January 2025.  https://legal.transkribus.org/terms. </li>

<li>Handwriting OCR Frequently Asked Questions Page. 2025. Accessed: 29 January 2025. https://www.handwritingocr.com/#faq. </li>

<li>Handwriting OCR Privacy Policy. 2025. Accessed: 29 January 2025. https://www.handwritingocr.com/privacy. </li>

</ul>

<p>
 Our plan is to propose options to the sponsor of viable ways to achieve the goal of transcribing archival documents using AI. 
</p>

## Lessons Learned

<p>
Information to follow... 
</p>

<p><a href="https://github.com/users/gahdez14/projects/1">Github Project Webpage</a></p>



