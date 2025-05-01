# Creative-projextv2
HI 4613: History of the Soviet Union, Spring 2025     Instructor: Stephen Brain, Ph.D.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Kirov Conspiracy: An Interactive Historical Investigation</title>
    <style>
        /* Soviet-inspired color scheme */
        body {
            font-family: 'Times New Roman', serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
            line-height: 1.6;
        }

        header {
            background-color: #c62828; /* Soviet red */
            color: #ffeb3b; /* Gold text */
            padding: 30px 0;
            text-align: center;
            border-bottom: 5px solid #212121;
        }

        header h1 {
            margin: 0;
            font-size: 2.2em;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }

        .subtitle {
            font-style: italic;
            margin-top: 10px;
        }

        main {
            margin: 20px auto;
            padding: 25px;
            background: white;
            border-radius: 5px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            max-width: 900px;
            border-left: 15px solid #c62828;
        }

        h2 {
            color: #c62828;
            border-bottom: 2px solid #c62828;
            padding-bottom: 5px;
        }

        img {
            max-width: 100%;
            height: auto;
            margin: 15px 0;
            border: 3px solid #ddd;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .document {
            background-color: #f5f5f5;
            padding: 15px;
            margin: 20px 0;
            border-left: 5px solid #c62828;
        }

        footer {
            margin-top: 30px;
            padding: 20px;
            background: #212121;
            color: white;
            text-align: center;
            font-size: 14px;
        }

        footer a {
            color: #ffeb3b;
            text-decoration: none;
        }

        .theory {
            background-color: #fffde7;
            padding: 15px;
            margin: 15px 0;
            border: 1px dashed #c62828;
        }

        .timeline {
            border-left: 3px solid #c62828;
            padding-left: 20px;
            margin: 20px 0;
        }

        .timeline-event {
            margin-bottom: 30px;
            position: relative;
        }

        .timeline-event:before {
            content: "";
            position: absolute;
            left: -26px;
            top: 5px;
            width: 15px;
            height: 15px;
            border-radius: 50%;
            background: #c62828;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>The Kirov Conspiracy</h1>
        <p class="subtitle">December 1, 1934: The Murder That Changed Soviet History</p>
    </header>

    <!-- Main Content Section -->
    <main>
        <section id="introduction">
            <h2>Case Overview</h2>
            <p>On December 1, 1934, Sergei Kirov, the popular Leningrad Party leader, was assassinated in the Smolny Institute. This mysterious murder became the catalyst for Stalin's Great Purge, but historians still debate: Did Stalin orchestrate the killing or merely exploit it?</p>
           <img src="images/download.jpg" alt="Descriptive text for the image">
           
        </section>

        <section id="crime-scene">
            <h2>The Crime Timeline</h2>
            <div class="timeline">
                <div class="timeline-event">
                    <h3>4:30 PM, December 1, 1934</h3>
                    <p>Leonid Nikolayev shoots Kirov in the hallway outside his office at the Smolny Institute</p>
                </div>
                <div class="timeline-event">
                    <h3>Within Hours</h3>
                    <p>Stalin personally takes charge of the investigation</p>
                </div>
                <div class="timeline-event">
                    <h3>December 2-29, 1934</h3>
                    <p>104 "accomplices" executed without trial</p>
                </div>
            </div>
        </section>

        <section id="theories">
            <h2>Competing Theories</h2>
            
            <div class="theory">
                <h3>Stalin's Plot</h3>
                <p><strong>Evidence:</strong></p>
                <ul>
                    <li>Kirov was becoming too popular after the 17th Party Congress</li>
                    <li>NKVD officers had detained Nikolayev twice before but released him</li>
                    <li>Kirov's bodyguard Borisov died in a suspicious "accident" before testifying</li>
                </ul>
            </div>
            
            <div class="theory">
                <h3>Lone Assassin</h3>
                <p><strong>Evidence:</strong></p>
                <ul>
                    <li>Nikolayev had personal grievances against Party leadership</li>
                    <li>No direct documentary evidence links Stalin to the murder</li>
                    <li>Stalin may have simply exploited the situation after the fact</li>
                </ul>
            </div>
        </section>

        <section id="documents">
            <h2>Key Documents</h2>
            
            <div class="document">
                <h3>NKVD Report (Excerpt)</h3>
                <p>"The assassin Nikolayev was apprehended at the scene... [REDACTED]... no evidence of wider conspiracy found... [REDACTED]... case closed by order of [REDACTED]."</p>
            </div>
            
            <img src="images.jpg" alt="Descriptive text for the image">
        </section>

        <section id="aftermath">
            <h2>Historical Consequences</h2>
            <p>The Kirov assassination became the justification for the Great Purge (1936-1938), during which:</p>
            <ul>
                <li>Over 700,000 people were executed</li>
                <li>Old Bolsheviks like Zinoviev and Kamenev were tried in show trials</li>
                <li>Stalin consolidated absolute power</li>
            </ul>
        </section>
    </main>

    <!-- Footer Section -->
    <footer>
        <p>
            Created by Andrew F. Martin for HI 4613: History of the Soviet Union, Spring 2025.<br>
            Primary source: Robert Conquest's <i>Stalin and the Kirov Murder</i> (1989)<br>
            <a href="[https://www.britannica.com/event/Kirov-murder](https://www.history.com/this-day-in-history/december-1/sergey-kirov-murdered)" target="_blank">Learn more at Encyclopedia Britannica</a>
        </p>
    </footer>
</body>
</html>
