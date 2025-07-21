<style>
    #content {
        display: flex
    }
    #side-nav {
        width: 20%;
    }
    #main {
        width: 80%;
    }
    .presentation-selector:hover {
        color: yellow;
        cursor: pointer;
    }
</style>

<div id="content">
    <div id="side-nav">
    <ul id="nav-list">
        <li id="feasibility" class="presentation-selector">Feasability</li>
        <li id="design" class="presentation-selector">Design</li>
    </ul>
    </div>
    <div id="main">
        <div id="feasibility-div" class="presentation-container">
        <div id="feasibility-title" class="presentation-title">
            <h2>Feasibility Presentation</h2>
            <button class="btn" onclick="window.open('../resources/FeasibilityPresentation.pdf', '_blank')">
            <i class="fas fa-file-pdf"></i> Download PDF</button>
            </div>
            <div>
                <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQJ_GKB92-LARDcygETfulac7tKayQNH6Xlz4C2rLquSOSwEsYniI4ValxkE2AgldgZvNQejXPCK_Fl/pubembed?start=false&loop=false&delayms=30000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
            </div>
        </div>

        <div id="design-div" class="presentation-container">
            <h2>Design Presentation</h2>
            <div>
                <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQHf2AkFWgbLi2ZpRqXf1apPY6Gb17mPtINmAO5MlbG2HJyhIPWzdPm82CZPcV53sE2ltGcZKIC8m-l/pubembed?start=false&loop=false&delayms=30000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
            </div>
        </div>
    </div>
</div>

<script>
    function hidePresentations(){ 
        let presentations = document.getElementsByClassName("presentation-container");
        for (let presentation of presentations){
                presentation.style.display = 'none';
        }
    }

    function showPresentation(presentationName){
        let divId = presentationName + "-div";
        let presentation = document.getElementById(divId);
        presentation.style.display = 'block';
    }

    document.addEventListener('click', function() {
        if (event.target.classList.contains('presentation-selector')){
            hidePresentations();
            showPresentation(event.target.id)
        }
    })

    hidePresentations();
    showPresentation('feasibility');

</script>