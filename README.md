# JS30 Speech Detection
Exercise 20 in WesBos' JavaScript30 tutorials. 

This was quite a bit of fun I think because of how relevant it is. The possibilities are endless with this, for times sake I chose to include a few sample sentences, and have the app open up an email contact upon saying the command "hire this dev".

    const emailDev = () => {
        window.location.assign("mailto:nikrowedev@gmail.com?Subject=" +
         encodeURIComponent('We love your work!') + 
        "&body=" +
        encodeURIComponent('Thanks for contacting me! You can erase this and put
         your message content here :) '));
    }

    if (transcript === 'hire this dev' || transcript === 'higher this Dev') {
        emailDev()
    }

<a href="https://nikrowedevjs30-speech-detection.netlify.app/">Demo</a>