
for (i = 1; i <= 6; i++)
{   var divContainer = document.getElementById(i.toString());
      divContainer.addEventListener("click", function(event)  
    {   const audio = document.getElementById('audio_' + event.target.id);
        audio.play();
            for (j = 1; j <= 6; j++) {
            document.getElementById(j.toString()).classList.remove("active");
        };
        const picActive = document.getElementById(event.target.id);
        picActive.className += " active";
  
       });
};




