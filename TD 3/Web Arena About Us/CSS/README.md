/* General Body Styling */
body {
    font-family: Verdana, sans-serif;
    background-color: #f9f9f9;
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    
    justify-content: center; background-image: url('Images/df-min.jpg'); /* Chemin relatif vers l'image */
    background-size: cover; /* L'image couvre toute la page */
    background-repeat: no-repeat; /* Pas de répétition */
    background-position: center; /* L'image est centrée */
    background-attachment: fixed; /* Le fond reste fixe lors du défilement */
    color: #333; /* Couleur du texte pour plus de lisibilité */
  }
  
  /* le style de Header  */
  header {
    background-color: #e85b03;
    color: white;
    padding: 40px;
    text-align: center;
    width: 100%;
  }
  
  /* le style de Header  */
  header h1 {
    font-size: 2.5rem;
    margin: 10px 0;
  }
  
  /* le style de Header  */
  header p {
    font-size: 1.2rem;
    margin: 5px 0;
  }
  
  .image-credit a {
    color: #ffffff;
    text-decoration: underline;
  }
  
  /* le style de Services Section  */
  .services {
    max-width: 50px;
    display: flex;
    gap: 30px;
    padding: 40px;
    flex-direction: reverse;
    width: 100%;
    max-width: 60%;
    margin-top: 300px 
  }
  
  
  /* pas toucher */
  .service-card {
    justify-content: center;
    background-color: #ff6200;
    color: white;
    padding: 20px;
    border-radius: 8px;
    width: 200px;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    place-items: center;
    
  
  }
  
  
  
  /* pas toucher */
  .service-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
    
  }
  
  .service-card h3 {
    font-size: 1.2rem;
    margin-bottom: 10px;
  }
  
  .service-card p {
    font-size: 0.9rem;
    line-height: 1.5;
  }
  
  
  .services-titre {
    background-color: #ff6200;
    color: white;
    padding: 10px;
    border-radius: 8px;
    width: 500px auto;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    margin-bottom: 300px;
  }
  
  
  /* le style de Footer  */
  footer {
    background-color: #000000;
    color: white;
    text-align: center;
    padding: 10px;
    width: 100%;
    margin-top: 20px;
  }
  
  footer p {
    font-size: 1rem;
    margin: 0;
  }
  
