# The Prisoners Dilemma (Spielbare Version)

**Please find the English version below**

Dies ist eine einfache, auf Flask basierende Webanwendung, die es Spielern ermöglicht, am Spiel „The Prisoners Dilemma“ teilzunehmen, bei dem sie Entscheidungen treffen können, um Jahre im Gefängnis zu sammeln. Das Spiel ist für zwei Spieler ausgelegt und umfasst Funktionen wie das Erstellen von Räumen, das Beitreten zu bestehenden Räumen und das Treffen von Entscheidungen, die sich auf das Spielergebnis auswirken.
## Funktionen
- Erstellen Sie einen Spielraum mit einem eindeutigen Raumcode.
- Mit dem Raumcode einem vorhandenen Spielraum beitreten.
- Spieler können wählen, ob sie den anderen verraten oder loyal bleiben wollen, was sich auf ihre Jahre im Gefängnis auswirkt.
- Zeigt aktuelle Jahre im Gefängnis und Spielerrollen an.
- Einfache und intuitive Benutzeroberfläche.
## Verwendete Technologien
- Flask: Ein leichtgewichtiges WSGI-Webanwendungs-Framework in Python.
- HTML/CSS: Für die Front-End-Benutzeroberfläche.
- JavaScript (jQuery): Für die Verarbeitung asynchroner Anfragen.
## Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/flask-game-app.git
   cd flask-game-app
   ```
2. **Set up a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. **Installieren Sie die erforderlichen Pakete**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Führen Sie die Anwendung aus**:
   ```bash
   python app.py
   ```
5. **Greifen Sie auf die Anwendung zu**:
   Öffnen Sie Ihren Webbrowser und gehen Sie zu „http://127.0.0.1:5000“.

## Spielregeln
Das Spiel basiert auf dem klassischen **Gefangenendilemma**, einem Standardbeispiel für ein spieltheoretisches Problem. Hier sind die Regeln:

1. **Hintergrundgeschichte**: Es gibt zwei Spieler im Spiel, Pimpleback Jim und Pimpleback Jims Freundin Babyface Kate. Sie planten gemeinsam einen Coup, bei dem sie ein Rollstuhlgeschäft ausrauben wollten, bewaffnet mit jeweils nur einem Löffel. Gerade als sie einen mittelpreisigen Stuhl erfolgreich geraubt hatten, traf die Polizei ein.
Auf dem Revier werden sie in getrennten Räumen verhört und beiden wird die gleiche Frage gestellt: „Wer hat das Verbrechen begangen? Sie oder Ihr Kollege?“ Nun stehen sie jeweils vor einer Wahl: Sie können entweder ihren Freund verraten, um ihre eigene Haut zu retten, oder sie können schweigen, denn Snitches get Stiches
2. **Entscheidungen**:
   - **Schweigen**: Wenn beide Spieler sich dafür entscheiden, zu schweigen, erhalten sie jeweils 1 Jahr Gefängnis.
   - **Verraten**: Wenn beide Spieler sich dafür entscheiden, den anderen zu verraten, erhalten sie jeweils 3 Jahre Gefängnis.
   - **Gemischte Entscheidungen**: Wenn ein Spieler schweigt, während der andere verrät, kommt der Verräter frei, während der Loyale 5 Jahre Gefängnis erhält.
3. **Runden**: Das Spiel besteht aus einer vorgegebenen Anzahl von Runden (zwischen 10 und 50). Nach jeder Runde können die Spieler die Ergebnisse ihrer Entscheidungen und die aktualisierten Punktzahlen einsehen.
4. **Gewinnen**: Der Spieler mit der niedrigsten Zahl an zu verbüßenden Jahren am Ende aller Runden wird zum Gewinner erklärt.
## Verwendung
1. **Raum erstellen**:
   - Klicken Sie auf die Schaltfläche „Raum erstellen“, um einen neuen Spielraum mit einem eindeutigen Code zu erstellen.
2. **Beitritt zu einem Raum**:
   - Geben Sie den Raumcode ein, um an einem bestehenden Spiel teilzunehmen.
3. **Treffen Sie Ihre Wahl**:
   - Sobald Sie im Spiel sind, können Sie sich für Schweigen oder Verrat entscheiden, indem Sie auf die entsprechenden Schaltflächen klicken.
4. **Spielstände anzeigen**:
   - Die aktuellen Spielstände und Spielerrollen werden auf dem Bildschirm angezeigt.
## Mitwirken
Beiträge sind willkommen! Wenn Sie Vorschläge für Verbesserungen oder neue Funktionen haben, können Sie gerne ein Issue eröffnen oder einen Pull-Request einreichen.
## Lizenz
Dieses Projekt ist unter der MIT-Lizenz lizenziert – siehe die Datei [LICENSE](LICENSE) für Details.
## Danksagungen
- Vielen Dank an die Flask-Community für ihre Unterstützung und Ressourcen.
- Inspiration aus verschiedenen Online-Tutorials und Dokumentationen.



# The Prisoners Dilemma (Playable version)

This is a simple Flask-based web application that allows players to participate in the prsioners dilemma game, where they can make choices to score points. The game is designed for two players, and it includes features such as room creation, joining existing rooms, and making choices that affect the game outcome.

## Features

- Create a game room with a unique room code.
- Join an existing game room using the room code.
- Players can choose to stay silent or betray, affecting their years in prison.
- Displays current years in prison and player roles.
- Simple and intuitive user interface.

## Technologies Used

- Flask: A lightweight WSGI web application framework in Python.
- HTML/CSS: For the front-end user interface.
- JavaScript (jQuery): For handling asynchronous requests.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/flask-game-app.git
   cd flask-game-app
   ```

2. **Set up a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages**:
   ```bash
   pip install -r requirements.txt
   ```


4. **Run the application**:
   ```bash
   python app.py
   ```

5. **Access the application**:
   Open your web browser and go to `http://127.0.0.1:5000`.

## Rules of the Game

The game is based on the classic **Prisoner's Dilemma** scenario, which is a standard example of a game theory problem. Here are the rules:


1. **Background story**: There are two players in the game, Pimpleback Jim and Pimpleback Jim's friend, Babyface Kate. They planned a coup together, where they intended to rob a wheelchair store, armed with just a spoon each. Just as they had succesfully robbed a moderatly expensive chair, the police arrived.

At the presinct they get put in seperate rooms for interrogation and both get asked the same question: "Who committed the crime? You or your colleague?". Now they are each faced with a choice, they can either throw their friend under the bus, trying to save their own skin, or they can stay silent since snithes get stiches.

2. **Choices**:
   - **Stay silent**: If both players choose to stay silent, they each get 1 year in prison.
   - **Betray**: If both players choose to betray the other one, they each get  3 years in prison.
   - **Mixed Choices**: If one player stays silent while the other betrays, the betrayer goes free, while the silent one gets 5 years in prison.

3. **Rounds**: The game consists of a predetermined number of rounds (between 10 and 50). After each round, players can see the results of their choices and the updated scores.

4. **Winning**: The player with the lowest number of years in prison at the end of all rounds is declared the winner.

## Usage

1. **Create a Room**:
   - Click on the "Create Room" button to generate a new game room with a unique code.

2. **Join a Room**:
   - Enter the room code to join an existing game.

3. **Make Your Choice**:
   - Once in the game, you can choose to cooperate or defect by clicking the respective buttons.

4. **View Scores**:
   - The current scores and player roles will be displayed on the screen.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

