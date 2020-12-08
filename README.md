# AI-Tic-Tac-Toe
This is a Tic Tac Toe game with an unbeatable AI ever possible !! (With game Demo)


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Tic Tac Toe</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <h1 class="me">ME</h1>
    <table class="scores_table_me">
        <tr>
            <td class="scoreboard">
                <h2>Wins</h2>
            </td>
            <td class="scoreboard">
                <h2>Losses</h2>
            </td>
        </tr>
        <tr>
            <td id="human_wins" class="scoreboard scores"></td>
            <td id="human_losses" class="scoreboard scores"></td>
        </tr>
    </table>

    <table class="game_board">
        <tr>
            <td class="cell" id="0"></td>
            <td class="cell" id="1"></td>
            <td class="cell" id="2"></td>
        </tr>
        <tr>
            <td class="cell" id="3"></td>
            <td class="cell" id="4"></td>
            <td class="cell" id="5"></td>
        </tr>
        <tr>
            <td class="cell" id="6"></td>
            <td class="cell" id="7"></td>
            <td class="cell" id="8"></td>
        </tr>
    </table>

    <h1 class="computer">COMPUTER</h1>
    <table class="scores_table_computer">
        <tr>
            <td class="scoreboard">
                <h2>Wins</h2>
            </td>
            <td class="scoreboard">
                <h2>Losses</h2>
            </td>
        </tr>
        <tr>
            <td id="computer_wins" class="scoreboard scores"></td>
            <td id="computer_losses" class="scoreboard scores"></td>
        </tr>
    </table>

    <div class="endgame">
        <div class="text"></div>
        <button onclick="startGame()" id="replay_button">Replay</button>
    </div>
    <script src="script.js"></script>
</body>

</html>
