# EosPhotobooth
Use an Canon EOS in a photobooth, there is linked to different social media platforms.

##Use Case
Run in full automatic mode, only controlled by one (hardware-)button.

1.	Press the button to start the automatic mode
2.	Show a LiveView with countdown (5..4..3..2..photo)
3.	Take a photo
4.	Upload it to Instagram or other social media platforms

##Core Functionality

* Implement the Canon EOS Digital SDK to use the control the major functions of an EOS
* Handle the APIs of Instagram, Facebook (Pages), Google-Photos to post the photos

##Additional Functionality

* Use an gfx engine to modify the photos with a watermark and a custom filter
* Hardwaresupport for QR reader, to identify the participants and add a specific description or hashtags 

#External resources
* A tutorial about the Canon SDK to remotly control DSLR cameras. From taking photos to using the LiveView. [Canon-EDSDK-Tutorial-in-Csharp](http://www.codeproject.com/Articles/688276/Canon-EDSDK-Tutorial-in-Csharp)
* InstaAPI is a CSharp(#) wrapper for Instagram API build in DotNET Framework 4. It is a simple, small library that uses Instagram's server-side flow for fetching access tokens. [InstaAPI](http://instaapi.codeplex.com/)
