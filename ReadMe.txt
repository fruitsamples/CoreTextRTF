"CoreTextRTF" illustrates how to use CoreText to draw rtf content in a Cocoa application.  

The main functionality demonstrated in this application is encapsulated in the -drawRect: and -createColumns methods in the file CoreTextView.m.  That is where all of the CoreText drawing and layout takes place.  

Interested readers will also want to look at the -readFromURL:ofType:error: method in the MyDocument.m file where the rtf file data is read into memory.  In this sample, that operation is very simple and only requires three lines of code.


Using the Sample
Build and run this sample in Xcode 3.0 or later and run the resulting application.  

When the application starts up choose the "Open..." command from the "File" menu and open the enclosed "CoreTextRTF Test Document.rtf" document.  The contents of the file will be displayed in a window.  Clicking on that window will cycle through displaying the rtf content in one, two, or three columns.


Feedback and Bug Reports
Please send all feedback about this sample by connecting to the Contact ADC
<http://developer.apple.com/contact/feedback.html> page.
Please submit any bug reports about this sample to the Bug Reporting
<http://developer.apple.com/bugreporter> page.