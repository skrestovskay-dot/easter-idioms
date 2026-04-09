<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Idioms Worksheet · Match & Complete Dialogues</title>
    <style>
        * {
            box-sizing: border-box;
        }
        body {
            background-color: #f0f4f8;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
        }
        .worksheet {
            max-width: 1100px;
            width: 100%;
            background: white;
            border-radius: 28px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            padding: 30px 35px;
        }
        h1 {
            font-size: 1.8rem;
            color: #1e466e;
            border-left: 8px solid #ffb347;
            padding-left: 18px;
            margin-top: 0;
            margin-bottom: 5px;
        }
        .sub {
            color: #4a627a;
            border-bottom: 2px solid #ffe0b5;
            padding-bottom: 12px;
            margin-bottom: 28px;
        }
        .task {
            background: #fefaf5;
            margin-bottom: 40px;
            border-radius: 24px;
            padding: 20px 25px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.05);
            border: 1px solid #ffe2c4;
        }
        .task-title {
            font-weight: bold;
            font-size: 1.3rem;
            background: #ffedd5;
            display: inline-block;
            padding: 5px 20px;
            border-radius: 40px;
            margin-bottom: 20px;
            color: #a4511b;
        }
        .match-grid {
            display: flex;
            gap: 40px;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .match-col {
            flex: 1;
            min-width: 250px;
        }
        .match-item {
            background: #fff;
            border: 1px solid #ffd9b5;
            border-radius: 50px;
            padding: 10px 18px;
            margin: 10px 0;
            display: flex;
            align-items: center;
            gap: 12px;
        }
        .match-num {
            font-weight: bold;
            background: #ffb347;
            color: white;
            width: 28px;
            height: 28px;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            border-radius: 30px;
            font-size: 0.85rem;
        }
        .match-text {
            flex: 1;
            font-size: 0.95rem;
        }
        .match-select {
            padding: 6px 10px;
            border-radius: 25px;
            border: 1px solid #ffb347;
            background: white;
            font-family: inherit;
            width: 130px;
        }
        .dialogue {
            background: #f8f4ef;
            border-radius: 20px;
            padding: 15px 20px;
            margin: 15px 0;
            border-left: 5px solid #ffb347;
        }
        .speaker {
            font-weight: bold;
            color: #1e466e;
        }
        .inline-gap {
            display: inline-block;
            min-width: 180px;
        }
        .inline-gap input {
            width: 190px;
            padding: 6px 12px;
            border-radius: 25px;
            border: 1px solid #ffb347;
            background: #fffef7;
            font-family: inherit;
            font-size: 0.9rem;
            text-align: center;
        }
        .inline-gap input:focus {
            outline: none;
            border-color: #ff8c00;
            background: #fff8e7;
        }
        button {
            background-color: #ffb347;
            border: none;
            padding: 12px 28px;
            font-size: 1rem;
            font-weight: bold;
            border-radius: 40px;
            cursor: pointer;
            margin-top: 12px;
            margin-right: 15px;
            transition: 0.1s;
            color: #2d3e50;
        }
        button:hover {
            background-color: #ff9f1a;
            transform: scale(0.98);
        }
        .answers {
            background: #e9f3e6;
            padding: 18px 22px;
            border-radius: 24px;
            margin-top: 20px;
            border-left: 8px solid #6fbf4c;
            display: none;
        }
        .answers.show {
            display: block;
        }
        .good {
            color: #2d6a4f;
            font-weight: bold;
        }
        footer {
            text-align: center;
            font-size: 0.8rem;
            color: gray;
            margin-top: 20px;
        }
        hr {
            margin: 20px 0;
        }
        .idiom-list {
            display: flex;
            flex-wrap: wrap;
            gap: 12px;
            margin-bottom: 20px;
            padding: 12px;
            background: #eef2fa;
            border-radius: 20px;
        }
        .idiom-badge {
            background: white;
            padding: 6px 14px;
            border-radius: 30px;
            border: 1px solid #ffb347;
            font-size: 0.85rem;
            font-weight: 500;
        }
        @media (max-width: 750px) {
            .worksheet { padding: 18px; }
            .match-grid { flex-direction: column; }
            .inline-gap input { width: 160px; }
        }
    </style>
</head>
<body>
<div class="worksheet">
    <h1>📖 Idioms Worksheet</h1>
    <div class="sub">Match the idioms with their meanings · Complete the dialogues</div>

    <!-- ==================== EXERCISE 1: MATCH ==================== -->
    <div class="task">
        <div class="task-title">🔗 Exercise 1: Match the idiom to its meaning</div>
        
        <div class="idiom-list">
            <span class="idiom-badge">1. to worship someone</span>
            <span class="idiom-badge">2. don't put all your eggs in one basket</span>
            <span class="idiom-badge">3. a chicken and egg situation</span>
            <span class="idiom-badge">4. be religious about something</span>
            <span class="idiom-badge">5. break bread together</span>
            <span class="idiom-badge">6. blessing in disguise</span>
            <span class="idiom-badge">7. to egg someone on</span>
        </div>

        <div class="match-grid">
            <div class="match-col">
                <div class="match-item">
                    <span class="match-num">a</span>
                    <span class="match-text">to share a meal with someone, often as a sign of friendship</span>
                    <select class="match-select" id="match_a">
                        <option value="">— select —</option>
                        <option value="1">1. to worship someone</option>
                        <option value="2">2. don't put all your eggs in one basket</option>
                        <option value="3">3. a chicken and egg situation</option>
                        <option value="4">4. be religious about something</option>
                        <option value="5">5. break bread together</option>
                        <option value="6">6. blessing in disguise</option>
                        <option value="7">7. to egg someone on</option>
                    </select>
                </div>
                <div class="match-item">
                    <span class="match-num">b</span>
                    <span class="match-text">do not risk everything on a single opportunity</span>
                    <select class="match-select" id="match_b">
                        <option value="">— select —</option>
                        <option value="1">1. to worship someone</option>
                        <option value="2">2. don't put all your eggs in one basket</option>
                        <option value="3">3. a chicken and egg situation</option>
                        <option value="4">4. be religious about something</option>
                        <option value="5">5. break bread together</option>
                        <option value="6">6. blessing in disguise</option>
                        <option value="7">7. to egg someone on</option>
                    </select>
                </div>
                <div class="match-item">
                    <span class="match-num">c</span>
                    <span class="match-text">something that seems bad at first but turns out good</span>
                    <select class="match-select" id="match_c">
                        <option value="">— select —</option>
                        <option value="1">1. to worship someone</option>
                        <option value="2">2. don't put all your eggs in one basket</option>
                        <option value="3">3. a chicken and egg situation</option>
                        <option value="4">4. be religious about something</option>
                        <option value="5">5. break bread together</option>
                        <option value="6">6. blessing in disguise</option>
                        <option value="7">7. to egg someone on</option>
                    </select>
                </div>
            </div>
            <div class="match-col">
                <div class="match-item">
                    <span class="match-num">d</span>
                    <span class="match-text">to be very dedicated and committed to something</span>
                    <select class="match-select" id="match_d">
                        <option value="">— select —</option>
                        <option value="1">1. to worship someone</option>
                        <option value="2">2. don't put all your eggs in one basket</option>
                        <option value="3">3. a chicken and egg situation</option>
                        <option value="4">4. be religious about something</option>
                        <option value="5">5. break bread together</option>
                        <option value="6">6. blessing in disguise</option>
                        <option value="7">7. to egg someone on</option>
                    </select>
                </div>
                <div class="match-item">
                    <span class="match-num">e</span>
                    <span class="match-text">to greatly admire or respect someone</span>
                    <select class="match-select" id="match_e">
                        <option value="">— select —</option>
                        <option value="1">1. to worship someone</option>
                        <option value="2">2. don't put all your eggs in one basket</option>
                        <option value="3">3. a chicken and egg situation</option>
                        <option value="4">4. be religious about something</option>
                        <option value="5">5. break bread together</option>
                        <option value="6">6. blessing in disguise</option>
                        <option value="7">7. to egg someone on</option>
                    </select>
                </div>
                <div class="match-item">
                    <span class="match-num">f</span>
                    <span class="match-text">a situation where it's hard to know which came first</span>
                    <select class="match-select" id="match_f">
                        <option value="">— select —</option>
                        <option value="1">1. to worship someone</option>
                        <option value="2">2. don't put all your eggs in one basket</option>
                        <option value="3">3. a chicken and egg situation</option>
                        <option value="4">4. be religious about something</option>
                        <option value="5">5. break bread together</option>
                        <option value="6">6. blessing in disguise</option>
                        <option value="7">7. to egg someone on</option>
                    </select>
                </div>
                <div class="match-item">
                    <span class="match-num">g</span>
                    <span class="match-text">to encourage someone to do something risky</span>
                    <select class="match-select" id="match_g">
                        <option value="">— select —</option>
                        <option value="1">1. to worship someone</option>
                        <option value="2">2. don't put all your eggs in one basket</option>
                        <option value="3">3. a chicken and egg situation</option>
                        <option value="4">4. be religious about something</option>
                        <option value="5">5. break bread together</option>
                        <option value="6">6. blessing in disguise</option>
                        <option value="7">7. to egg someone on</option>
                    </select>
                </div>
            </div>
        </div>
    </div>

    <!-- ==================== EXERCISE 2: DIALOGUES ==================== -->
    <div class="task">
        <div class="task-title">💬 Exercise 2: Complete the dialogues</div>
        <div>🔹 Fill in each gap with the correct idiom from Exercise 1.</div>

        <!-- Dialogue 1 -->
        <div class="dialogue">
            <div><span class="speaker">Sarah:</span> "I'm thinking of investing all my savings into this project."</div>
            <div><span class="speaker">Tom:</span> "Be careful. <span class="inline-gap"><input type="text" id="dialog1" placeholder="idiom" size="30"></span> It's better to diversify your portfolio."</div>
        </div>

        <!-- Dialogue 2 -->
        <div class="dialogue">
            <div><span class="speaker">Emily:</span> "I lost my job last week."</div>
            <div><span class="speaker">Mike:</span> "I'm sorry to hear that. But maybe it's a <span class="inline-gap"><input type="text" id="dialog2" placeholder="idiom" size="30"></span>. You can take some time to figure out what you really want to do."</div>
        </div>

        <!-- Dialogue 3 -->
        <div class="dialogue">
            <div><span class="speaker">Karen:</span> "I'm trying to lose weight, so I've been <span class="inline-gap"><input type="text" id="dialog3" placeholder="idiom" size="30"></span> going to the gym every day."</div>
            <div><span class="speaker">David:</span> "That's great! Keep up the good work."</div>
        </div>

        <!-- Dialogue 4 -->
        <div class="dialogue">
            <div><span class="speaker">Alex:</span> "I really <span class="inline-gap"><input type="text" id="dialog4" placeholder="idiom" size="30"></span> Beyoncé. She's such an amazing performer."</div>
            <div><span class="speaker">Sophie:</span> "I agree. She's definitely one of the greatest entertainers of our time."</div>
        </div>

        <!-- Dialogue 5 -->
        <div class="dialogue">
            <div><span class="speaker">Mark:</span> "I need experience to get a job, but I can't get experience without a job. It's <span class="inline-gap"><input type="text" id="dialog5" placeholder="idiom" size="30"></span>."</div>
            <div><span class="speaker">Emily:</span> "I know what you mean. It can be really frustrating."</div>
        </div>

        <!-- Dialogue 6 -->
        <div class="dialogue">
            <div><span class="speaker">Kate:</span> "I'm thinking of asking my boss for a raise."</div>
            <div><span class="speaker">John:</span> "Go for it! I'll be there to <span class="inline-gap"><input type="text" id="dialog6" placeholder="idiom" size="30"></span>."</div>
        </div>
    </div>

    <div style="display: flex; gap: 15px; flex-wrap: wrap;">
        <button id="checkBtn">✅ Check my answers</button>
        <button id="resetBtn">🔄 Clear all</button>
    </div>

    <div id="answerKey" class="answers">
        <strong>📋 RESULTS & ANSWER KEY</strong><br>
        <div id="keyContent"></div>
    </div>
    <footer>⭐ Idioms are fixed expressions — learn them as whole phrases!</footer>
</div>

<script>
    // Correct matches: letter -> idiom number
    const correctMatches = {
        a: 5,   // break bread together
        b: 2,   // don't put all your eggs in one basket
        c: 6,   // blessing in disguise
        d: 4,   // be religious about something
        e: 1,   // to worship someone
        f: 3,   // a chicken and egg situation
        g: 7    // to egg someone on
    };

    // Correct idioms for dialogues (full phrases)
    const correctDialogs = [
        "don't put all your eggs in one basket",
        "blessing in disguise",
        "religious about",
        "worship",
        "a chicken and egg situation",
        "egg you on"
    ];

    // Acceptable variations for dialog answers
    const dialogVariations = {
        "don't put all your eggs in one basket": ["don't put all your eggs in one basket", "don't put all your eggs in one basket.", "do not put all your eggs in one basket"],
        "blessing in disguise": ["blessing in disguise", "a blessing in disguise"],
        "religious about": ["religious about", "religious about it", "religious about going"],
        "worship": ["worship", "worship someone", "worship her"],
        "a chicken and egg situation": ["a chicken and egg situation", "chicken and egg situation", "a chicken-and-egg situation", "a chicken and egg"],
        "egg you on": ["egg you on", "egg you on.", "egg on"]
    };

    function normalize(str) {
        return str.trim().toLowerCase().replace(/[.!?]$/, '').replace(/\s+/g, ' ').trim();
    }

    function isDialogCorrect(userAnswer, correctAnswer) {
        let userNorm = normalize(userAnswer);
        let correctNorm = normalize(correctAnswer);
        
        if (userNorm === correctNorm) return true;
        
        if (dialogVariations[correctAnswer]) {
            for (let varAns of dialogVariations[correctAnswer]) {
                if (userNorm === normalize(varAns)) return true;
            }
        }
        // Special case for "egg you on"
        if (correctAnswer === "egg you on" && (userNorm.includes("egg") && userNorm.includes("on"))) return true;
        if (correctAnswer === "religious about" && (userNorm.includes("religious") && userNorm.includes("about"))) return true;
        if (correctAnswer === "worship" && userNorm.includes("worship")) return true;
        
        return false;
    }

    function checkTasks() {
        let score = 0;
        let total = 0;
        let feedback = "";

        // ========== EXERCISE 1: Check matches ==========
        const matchLetters = ['a', 'b', 'c', 'd', 'e', 'f', 'g'];
        for (let letter of matchLetters) {
            let selectEl = document.getElementById(`match_${letter}`);
            let selectedValue = selectEl.value;
            let correctValue = correctMatches[letter].toString();
            total++;
            if (selectedValue === correctValue) {
                score++;
            } else {
                let selectedText = selectEl.options[selectEl.selectedIndex]?.text || "nothing";
                let correctText = "";
                for (let [key, val] of Object.entries(correctMatches)) {
                    if (key === letter) {
                        if (val === 1) correctText = "to worship someone";
                        else if (val === 2) correctText = "don't put all your eggs in one basket";
                        else if (val === 3) correctText = "a chicken and egg situation";
                        else if (val === 4) correctText = "be religious about something";
                        else if (val === 5) correctText = "break bread together";
                        else if (val === 6) correctText = "blessing in disguise";
                        else if (val === 7) correctText = "to egg someone on";
                    }
                }
                feedback += `Match ${letter.toUpperCase()}: "${selectedText}" ❌ correct: ${correctText}\n`;
            }
        }

        // ========== EXERCISE 2: Check dialogues ==========
        for (let i = 1; i <= 6; i++) {
            let userAnswer = document.getElementById(`dialog${i}`).value;
            let correctAnswer = correctDialogs[i-1];
            total++;
            if (isDialogCorrect(userAnswer, correctAnswer)) {
                score++;
            } else {
                feedback += `Dialogue ${i}: "${userAnswer}" ❌ correct: "${correctAnswer}"\n`;
            }
        }

        let percentage = Math.round((score/total)*100);
        let keyDiv = document.getElementById("keyContent");
        keyDiv.innerHTML = `<strong class="good">Your score: ${score} / ${total} (${percentage}%)</strong><br><br>`;
        
        if (feedback !== "") {
            keyDiv.innerHTML += `<span style="white-space: pre-line; font-size: 0.9rem;">${feedback}</span><br><hr>`;
        } else {
            keyDiv.innerHTML += `🎉🎉 PERFECT! Great job with the idioms! 🎉🎉<br><hr>`;
        }
        
        // Full answer key
        keyDiv.innerHTML += `
            <b>📌 ANSWER KEY:</b><br><br>
            <b>Exercise 1 (Matching):</b><br>
            &nbsp;&nbsp;a → 5 (break bread together)<br>
            &nbsp;&nbsp;b → 2 (don't put all your eggs in one basket)<br>
            &nbsp;&nbsp;c → 6 (blessing in disguise)<br>
            &nbsp;&nbsp;d → 4 (be religious about something)<br>
            &nbsp;&nbsp;e → 1 (to worship someone)<br>
            &nbsp;&nbsp;f → 3 (a chicken and egg situation)<br>
            &nbsp;&nbsp;g → 7 (to egg someone on)<br><br>
            <b>Exercise 2 (Dialogues):</b><br>
            &nbsp;&nbsp;1. don't put all your eggs in one basket<br>
            &nbsp;&nbsp;2. blessing in disguise<br>
            &nbsp;&nbsp;3. religious about<br>
            &nbsp;&nbsp;4. worship<br>
            &nbsp;&nbsp;5. a chicken and egg situation<br>
            &nbsp;&nbsp;6. egg you on<br>
            <hr>
            <i>💡 Tip: Idioms are fixed expressions — try to memorize them as whole phrases!</i>
        `;
        document.getElementById("answerKey").classList.add("show");
    }

    function resetAll() {
        // Reset selects
        const selects = document.querySelectorAll('select');
        selects.forEach(select => select.value = '');
        
        // Reset text inputs
        const inputs = document.querySelectorAll('input');
        inputs.forEach(input => input.value = '');
        
        document.getElementById("answerKey").classList.remove("show");
    }

    document.getElementById("checkBtn").addEventListener("click", checkTasks);
    document.getElementById("resetBtn").addEventListener("click", resetAll);
</script>
</body>
</html>
