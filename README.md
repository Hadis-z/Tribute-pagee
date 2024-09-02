# Tribute-pagee
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="./styles.css" rel="stylesheet">
    <title>Albert Einstein Tribute</title>
<body>
    <header>
        <div class="header-container">
            <img src="https://upload.wikimedia.org/wikipedia/commons/e/e9/Albert_Einstein_1921_by_F_Schmutzer_-_restoration.jpg" alt="Einstein in 1921">
            <div class="header-text">
                <h1>Albert Einstein</h1>
            </div>
        </div>
    </header>
     <main id="main">
        <h2 id="title">Albert Einstein: A Genius Remembered</h2>

  <figure id="img-div">
            <img id="image" src="https://upload.wikimedia.org/wikipedia/commons/d/d3/Albert_Einstein_Head.jpg" alt="Albert Einstein">
            <figcaption id="img-caption">Albert Einstein, one of the most influential physicists of the 20th century.</figcaption>
        </figure>

  <section id="tribute-info">
            <p>Albert Einstein was a theoretical physicist who developed the theory of relativity, one of the two pillars of modern physics (alongside quantum mechanics). His work is also known for its influence on the philosophy of science. He is best known to the general public for his mass–energy equivalence formula E = mc<sup>2</sup>, which has been dubbed "the world's most famous equation".</p>
            <p>Born in Ulm, Germany, in 1879, Einstein grew up in Munich, where he later began his schooling. His interest in mathematics and science was apparent from an early age, and by the age of 12, he had taught himself algebra and Euclidean geometry. In 1905, during his annus mirabilis (miracle year), he published four groundbreaking papers that laid the foundation for modern physics.</p>
            <p>In 1921, he received the Nobel Prize in Physics for his explanation of the photoelectric effect, a pivotal step in the development of quantum theory. He spent his later years at the Institute for Advanced Study in Princeton, New Jersey, where he continued to work on his theories until his death in 1955.</p>
         </section>

  <section class="timeline">
            <h2>Timeline of Major Events</h2>
            <ul>
                <li><strong>1879:</strong> Born in Ulm, Germany</li>
                <li><strong>1905:</strong> Published the theory of special relativity</li>
                <li><strong>1915:</strong> Formulated the general theory of relativity</li>
                <li><strong>1921:</strong> Awarded the Nobel Prize in Physics</li>
                <li><strong>1933:</strong> Emigrated to the United States</li>
                <li><strong>1955:</strong> Passed away in Princeton, New Jersey</li>
            </ul>
        </section>
        <main>
        <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
     header {
            background-color: #333;
            color: #fff;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
.header-container {
            position: relative;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }
 header img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            opacity: 0.8;
        }
  .header-text {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: #fff;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }
 h1 {
            margin: 0;
            font-size: 2.5em;
        }
  #main {
            padding: 20px;
            max-width: 800px;
            margin: auto;
        }
 #title {
            text-align: center;
            font-size: 2em;
            margin-bottom: 20px;
        }
#img-div {
            text-align: center;
            margin-bottom: 20px;
        }
 #image {
            display: block;
            max-width: 100%;
            height: auto;
            margin: 0 auto;
            border-radius: 0;
        }
  #img-caption {
            margin-top: 10px;
            font-style: italic;
        }
 #tribute-info {
            text-align: justify;
            margin-bottom: 20px;
        }
.timeline {
            background-color: #fff;
            padding: 20px;
        }
.timeline li {
            padding: 10px;
            border-bottom: 1px solid #000;
        }
 footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
 #tribute-link {
            color: #ffc107;
            text-decoration: none;
        }
        </style>
    </main>
     </body>
    <footer>
        <p>Learn more about Einstein's life and contributions to science on 
        <a id="tribute-link" href="https://en.wikipedia.org/wiki/Albert_Einstein" target="_blank">Wikipedia</a></p>
    </footer>
</html>
