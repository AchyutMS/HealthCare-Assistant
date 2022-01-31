# HealthCare-Assistant
HealthCare Chatbot that predicts the disease based on the symptoms given
<div class="grid">
    <div class="main">
      <h1>
        HealthCare Assistant
      </h1>

      <p class="subtitle">
        Submission for IEI Hackathon v1.0 by Team Maria
      </p>

      <h2 style="margin-top: 1em">About</h2>
      <p style="margin-top: 0.5em">
        HealthCare Assistant is an ML-driven chatbot that will assist you in analyzing your symptoms and predicting the disease.
        The chatbot can respond to your queries only to the of the knowledge base, so it is adviced to crosscheck the responses 
        with a medical professional.
      </p>

      <h2 style="margin-top: 1em">Problem Statement</h2>
      <p style="margin-top: 0.5em">
        For ages, having a good healthcare is a luxury for many people. It is not safe if people start making 
        assumptions about their symptoms and take medications on their own.
      </p>


      <h2 style="margin-top: 1em">Solution We Provide</h2>
      <p style="margin-top: 0.5em">
        A conversational bot that can predict the user's disease upto some extent and can advice them to visit the 
        respective doctors.
      </p>


      <p style="margin-top: 0.5em">
        Note:
        <b>This Bot can attempt to answer your queries about a limited set of
        diseases as of now. It can tell you about its description and some treatment. 
        
        We can make this bot more effective by expanding the knowlege base and making it ask for further questions (age, further symptoms, etc...)
        to increase the accuracy of it's prediction.
        </b>
      </p>


      <h2 style="margin-top: 1em">How Does It Work?</h2>
      <p style="margin-top: 0.5em">
        <ol>
            <li>We have built a knowledge database for limited diseases, their symptoms and their self-help treatments.</li>
            <li>Then, we transform the intents from the database to a Pytorch model.</li>
            <li>We then Built a chatbot framework to process the responses.</li>
            <li>We can access the bot from the website after integrating the chatbot framework.</li>
        </ol>
      </p>

      <h2 style="margin-top: 1em">Product Flow and Its Underlying Architecture</h2>
      <p style="margin-top: 0.5em">
        <img src="./images/product_flow.png" alt="image">
        <br>
        <br>
        <img src="./images/bag_of_words.jpeg" alt="image" width="600px">
        <br>
        <br>
        <img src="./images/feed_forward.jpeg" alt="image" width="600px">
      </p>


    </div>
    <div></div>
  </div>
