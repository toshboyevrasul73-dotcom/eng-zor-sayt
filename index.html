<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eng Zor Sayt - Ingliz Tilini O'rganish Platformasi</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap');
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
        }
        .flip-card {
            background-color: transparent;
            perspective: 1000px;
        }
        .flip-card-inner {
            position: relative;
            width: 100%;
            height: 100%;
            text-align: center;
            transition: transform 0.6s;
            transform-style: preserve-3d;
        }
        .flip-card.flipped .flip-card-inner {
            transform: rotateY(180deg);
        }
        .flip-card-front, .flip-card-back {
            position: absolute;
            width: 100%;
            height: 100%;
            -webkit-backface-visibility: hidden;
            backface-visibility: hidden;
            border-radius: 1.5rem;
        }
        .flip-card-back {
            transform: rotateY(180deg);
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 min-h-screen flex flex-col">

    <!-- Header Navigation -->
    <header class="sticky top-0 z-50 bg-white/80 backdrop-blur-md border-b border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <!-- Logo -->
                <div class="flex items-center gap-3">
                    <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-indigo-600 to-violet-500 flex items-center justify-center text-white font-bold text-xl shadow-lg shadow-indigo-500/20">
                        <i data-lucide="sparkles" class="w-5 h-5"></i>
                    </div>
                    <div>
                        <span class="font-extrabold text-xl bg-gradient-to-r from-indigo-600 to-violet-600 bg-clip-text text-transparent">eng-zor-sayt</span>
                        <span class="text-xs text-slate-400 block -mt-1 font-medium">Ingliz tili platformasi</span>
                    </div>
                </div>

                <!-- Navigation Tabs -->
                <nav class="hidden md:flex items-center space-x-1 bg-slate-100 p-1.5 rounded-2xl">
                    <button onclick="switchTab('flashcards')" id="tab-flashcards" class="nav-btn flex items-center gap-2 px-4 py-2 rounded-xl text-sm font-semibold transition-all duration-200 bg-white text-indigo-600 shadow-sm">
                        <i data-lucide="layers" class="w-4 h-4"></i>
                        <span>So'zlar</span>
                    </button>
                    <button onclick="switchTab('quiz')" id="tab-quiz" class="nav-btn flex items-center gap-2 px-4 py-2 rounded-xl text-sm font-semibold text-slate-600 hover:text-slate-900 transition-all duration-200">
                        <i data-lucide="help-circle" class="w-4 h-4"></i>
                        <span>Viktorina</span>
                    </button>
                    <button onclick="switchTab('matching')" id="tab-matching" class="nav-btn flex items-center gap-2 px-4 py-2 rounded-xl text-sm font-semibold text-slate-600 hover:text-slate-900 transition-all duration-200">
                        <i data-lucide="gamepad-2" class="w-4 h-4"></i>
                        <span>Juftlikni top</span>
                    </button>
                </nav>

                <!-- User Stats -->
                <div class="flex items-center gap-3">
                    <div class="flex items-center gap-1.5 bg-amber-50 text-amber-700 px-3 py-1.5 rounded-full border border-amber-200 font-bold text-sm">
                        <i data-lucide="zap" class="w-4 h-4 fill-amber-500 text-amber-500"></i>
                        <span id="score-display">0</span> XP
                    </div>
                </div>
            </div>
        </div>

        <!-- Mobile Navigation -->
        <div class="md:hidden border-t border-slate-100 flex justify-around p-2 bg-white">
            <button onclick="switchTab('flashcards')" id="mob-tab-flashcards" class="flex flex-col items-center gap-1 text-xs font-semibold text-indigo-600 p-2">
                <i data-lucide="layers" class="w-5 h-5"></i>
                So'zlar
            </button>
            <button onclick="switchTab('quiz')" id="mob-tab-quiz" class="flex flex-col items-center gap-1 text-xs font-semibold text-slate-500 p-2">
                <i data-lucide="help-circle" class="w-5 h-5"></i>
                Viktorina
            </button>
            <button onclick="switchTab('matching')" id="mob-tab-matching" class="flex flex-col items-center gap-1 text-xs font-semibold text-slate-500 p-2">
                <i data-lucide="gamepad-2" class="w-5 h-5"></i>
                O'yin
            </button>
        </div>
    </header>

    <!-- Main Content Area -->
    <main class="flex-grow max-w-5xl w-full mx-auto px-4 py-8">

        <!-- FLASHCARDS SECTION -->
        <section id="section-flashcards" class="space-y-6">
            <div class="text-center max-w-xl mx-auto mb-8">
                <h1 class="text-3xl font-extrabold text-slate-900 sm:text-4xl">Bugungi Lug'at Boyligi</h1>
                <p class="text-slate-500 mt-2">Kartochkani bosish orqali tarjimasini ko'ring hamda talaffuzini eshiting.</p>
            </div>

            <!-- Card Viewer -->
            <div class="max-w-md mx-auto">
                <div id="flashcard-container" class="flip-card h-80 w-full cursor-pointer group" onclick="toggleCardFlip()">
                    <div class="flip-card-inner shadow-xl shadow-indigo-100 border border-slate-200 rounded-3xl">
                        <!-- Front side -->
                        <div class="flip-card-front bg-white p-8 flex flex-col justify-between items-center">
                            <div class="w-full flex justify-between items-center text-xs font-semibold uppercase tracking-wider text-indigo-600 bg-indigo-50 px-3 py-1.5 rounded-full">
                                <span>Inglizcha</span>
                                <span id="card-category">Lug'at</span>
                            </div>
                            <div class="text-center space-y-3 my-auto">
                                <h2 id="card-word" class="text-4xl font-extrabold text-slate-800">Adventure</h2>
                                <p id="card-phonetic" class="text-slate-400 font-mono text-lg">/ədˈven.tʃər/</p>
                                <button onclick="event.stopPropagation(); speakCurrentWord();" class="mt-2 inline-flex items-center gap-2 px-4 py-2 bg-indigo-50 hover:bg-indigo-100 text-indigo-600 font-semibold rounded-xl transition-all">
                                    <i data-lucide="volume-2" class="w-5 h-5"></i>
                                    Tinglash
                                </button>
                            </div>
                            <div class="text-slate-400 text-xs flex items-center gap-1">
                                <i data-lucide="rotate-cw" class="w-3.5 h-3.5"></i>
                                Orqasini ko'rish uchun bosing
                            </div>
                        </div>

                        <!-- Back side -->
                        <div class="flip-card-back bg-gradient-to-br from-indigo-600 to-violet-700 text-white p-8 flex flex-col justify-between items-center">
                            <div class="w-full flex justify-between items-center text-xs font-semibold uppercase tracking-wider text-indigo-200 bg-white/10 px-3 py-1.5 rounded-full">
                                <span>O'zbekcha Tarjimasi</span>
                            </div>
                            <div class="text-center space-y-4 my-auto">
                                <h2 id="card-translation" class="text-3xl font-extrabold">Sarguzasht</h2>
                                <div class="bg-white/10 p-4 rounded-2xl backdrop-blur-sm border border-white/10 max-w-xs">
                                    <p id="card-example" class="text-sm text-indigo-100 italic">"Life is a bold adventure or nothing at all."</p>
                                </div>
                            </div>
                            <div class="text-indigo-200 text-xs flex items-center gap-1">
                                <i data-lucide="sparkles" class="w-3.5 h-3.5"></i>
                                Yana bir bor bosib qayting
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Navigation Controls -->
                <div class="flex items-center justify-between mt-6 px-4">
                    <button onclick="prevCard()" class="p-3 bg-white hover:bg-slate-50 rounded-2xl border border-slate-200 shadow-sm text-slate-700 font-semibold transition-all hover:scale-105 active:scale-95 flex items-center gap-2">
                        <i data-lucide="arrow-left" class="w-5 h-5"></i>
                        <span>Oldingi</span>
                    </button>
                    <span id="card-counter" class="text-sm font-semibold text-slate-500 bg-slate-200/60 px-4 py-2 rounded-full">1 / 5</span>
                    <button onclick="nextCard()" class="p-3 bg-indigo-600 hover:bg-indigo-700 rounded-2xl shadow-md text-white font-semibold transition-all hover:scale-105 active:scale-95 flex items-center gap-2">
                        <span>Keyingi</span>
                        <i data-lucide="arrow-right" class="w-5 h-5"></i>
                    </button>
                </div>
            </div>
        </section>

        <!-- QUIZ SECTION -->
        <section id="section-quiz" class="hidden max-w-xl mx-auto space-y-6">
            <div class="bg-white p-8 rounded-3xl border border-slate-200 shadow-xl space-y-6">
                <!-- Quiz Header -->
                <div class="flex justify-between items-center border-b border-slate-100 pb-4">
                    <div>
                        <span class="text-xs font-bold text-indigo-600 uppercase tracking-wider">Test Sinovi</span>
                        <h2 class="text-xl font-bold text-slate-800">To'g'ri tarjimani tanlang</h2>
                    </div>
                    <span id="quiz-progress" class="text-sm font-bold text-slate-400">1/5</span>
                </div>

                <!-- Question -->
                <div class="text-center py-4">
                    <span class="text-sm text-slate-400 uppercase tracking-wider block mb-1">Inglizcha So'z:</span>
                    <h3 id="quiz-question-word" class="text-3xl font-extrabold text-slate-900">Explore</h3>
                </div>

                <!-- Options Grid -->
                <div id="quiz-options" class="grid grid-cols-1 gap-3">
                    <!-- Dynamic Buttons Generated Here -->
                </div>

                <!-- Feedback Message -->
                <div id="quiz-feedback" class="hidden p-4 rounded-2xl text-center font-bold text-sm"></div>
            </div>
        </section>

        <!-- MATCHING GAME SECTION -->
        <section id="section-matching" class="hidden max-w-2xl mx-auto space-y-6">
            <div class="text-center max-w-md mx-auto mb-6">
                <h2 class="text-2xl font-extrabold text-slate-900">Juftliklarni Moslang</h2>
                <p class="text-slate-500 text-sm mt-1">Inglizcha so'zlar va ularning o'zbekcha ma'nosini bir-biriga moslashtiring.</p>
            </div>

            <!-- Matching Grid -->
            <div id="matching-grid" class="grid grid-cols-2 gap-4">
                <!-- Dynamic Matching Cards Generated Here -->
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="mt-auto border-t border-slate-200 bg-white py-6">
        <div class="max-w-7xl mx-auto px-4 text-center text-sm text-slate-500">
            <p>© 2026 <span class="font-bold text-indigo-600">eng-zor-sayt</span>. Barcha huquqlar himoyalangan.</p>
        </div>
    </footer>

    <!-- JavaScript Logic -->
    <script>
        // Data Set
        const wordsData = [
            {
                word: "Adventure",
                phonetic: "/ədˈven.tʃər/",
                translation: "Sarguzasht",
                example: "Life is a bold adventure or nothing at all.",
                category: "Sayohat"
            },
            {
                word: "Explore",
                phonetic: "/ɪkˈsplɔːr/",
                translation: "Tadqiq qilmoq / Izlamoq",
                example: "We need to explore new opportunities.",
                category: "Harakat"
            },
            {
                word: "Opportunity",
                phonetic: "/ˌɒp.əˈtʃuː.nə.ti/",
                translation: "Imkoniyat",
                example: "Education creates new opportunities.",
                category: "Kelajak"
            },
            {
                word: "Knowledge",
                phonetic: "/ˈnɒl.ɪdʒ/",
                translation: "Bilim / Ma'lumot",
                example: "Knowledge is power in the modern world.",
                category: "Ta'lim"
            },
            {
                word: "Success",
                phonetic: "/səkˈses/",
                translation: "Muvaffaqiyat",
                example: "Hard work is the key to success.",
                category: "Natija"
            }
        ];

        // State Variables
        let currentCardIndex = 0;
        let score = 0;
        let currentQuizIndex = 0;
        let selectedMatchingWord = null;
        let matchedPairsCount = 0;

        // Initialize Lucide Icons
        lucide.createIcons();

        // Switch Tabs
        function switchTab(tab) {
            // Hide all sections
            document.getElementById('section-flashcards').classList.add('hidden');
            document.getElementById('section-quiz').classList.add('hidden');
            document.getElementById('section-matching').classList.add('hidden');

            // Reset navigation styles
            document.querySelectorAll('.nav-btn').forEach(btn => {
                btn.className = "nav-btn flex items-center gap-2 px-4 py-2 rounded-xl text-sm font-semibold text-slate-600 hover:text-slate-900 transition-all duration-200";
            });

            // Show selected section
            document.getElementById(`section-${tab}`).classList.remove('hidden');
            document.getElementById(`tab-${tab}`).className = "nav-btn flex items-center gap-2 px-4 py-2 rounded-xl text-sm font-semibold transition-all duration-200 bg-white text-indigo-600 shadow-sm";

            // Trigger Section Specific Setup
            if(tab === 'quiz') startQuiz();
            if(tab === 'matching') startMatchingGame();
        }

        // --- FLASHCARDS LOGIC ---
        function updateCardDisplay() {
            const data = wordsData[currentCardIndex];
            const card = document.getElementById('flashcard-container');
            
            // Unflip card
            card.classList.remove('flipped');

            setTimeout(() => {
                document.getElementById('card-word').innerText = data.word;
                document.getElementById('card-phonetic').innerText = data.phonetic;
                document.getElementById('card-translation').innerText = data.translation;
                document.getElementById('card-example').innerText = `"${data.example}"`;
                document.getElementById('card-category').innerText = data.category;
                document.getElementById('card-counter').innerText = `${currentCardIndex + 1} / ${wordsData.length}`;
            }, 150);
        }

        function toggleCardFlip() {
            document.getElementById('flashcard-container').classList.toggle('flipped');
        }

        function nextCard() {
            currentCardIndex = (currentCardIndex + 1) % wordsData.length;
            updateCardDisplay();
        }

        function prevCard() {
            currentCardIndex = (currentCardIndex - 1 + wordsData.length) % wordsData.length;
            updateCardDisplay();
        }

        function speakCurrentWord() {
            const word = wordsData[currentCardIndex].word;
            const utterance = new SpeechSynthesisUtterance(word);
            utterance.lang = 'en-US';
            window.speechSynthesis.speak(utterance);
        }

        // --- QUIZ LOGIC ---
        function startQuiz() {
            currentQuizIndex = 0;
            showQuizQuestion();
        }

        function showQuizQuestion() {
            const currentItem = wordsData[currentQuizIndex];
            document.getElementById('quiz-question-word').innerText = currentItem.word;
            document.getElementById('quiz-progress').innerText = `${currentQuizIndex + 1}/${wordsData.length}`;
            document.getElementById('quiz-feedback').classList.add('hidden');

            // Generate Options (1 correct + 3 random choices)
            let options = [currentItem.translation];
            while (options.length < 4) {
                let randomOpt = wordsData[Math.floor(Math.random() * wordsData.length)].translation;
                if (!options.includes(randomOpt)) {
                    options.push(randomOpt);
                }
            }

            // Shuffle options
            options.sort(() => Math.random() - 0.5);

            const optionsContainer = document.getElementById('quiz-options');
            optionsContainer.innerHTML = '';

            options.forEach(opt => {
                const btn = document.createElement('button');
                btn.className = "p-4 text-left font-semibold rounded-2xl border border-slate-200 hover:border-indigo-500 hover:bg-indigo-50/50 transition-all text-slate-700 flex justify-between items-center group";
                btn.innerHTML = `<span>${opt}</span> <i data-lucide="circle" class="w-5 h-5 text-slate-300 group-hover:text-indigo-500"></i>`;
                btn.onclick = () => checkQuizAnswer(opt, currentItem.translation, btn);
                optionsContainer.appendChild(btn);
            });

            lucide.createIcons();
        }

        function checkQuizAnswer(selected, correct, selectedBtn) {
            const feedback = document.getElementById('quiz-feedback');
            const allBtns = document.getElementById('quiz-options').children;

            // Disable all buttons
            for (let btn of allBtns) {
                btn.disabled = true;
            }

            if (selected === correct) {
                selectedBtn.className = "p-4 text-left font-semibold rounded-2xl border-2 border-emerald-500 bg-emerald-50 text-emerald-800 flex justify-between items-center";
                selectedBtn.querySelector('i').replaceWith(createIconElement('check-circle-2', 'text-emerald-500'));
                
                score += 10;
                updateScoreDisplay();

                feedback.className = "p-4 rounded-2xl text-center font-bold text-sm bg-emerald-100 text-emerald-800 border border-emerald-200";
                feedback.innerText = "To'g'ri javob! +10 XP";
            } else {
                selectedBtn.className = "p-4 text-left font-semibold rounded-2xl border-2 border-rose-500 bg-rose-50 text-rose-800 flex justify-between items-center";
                selectedBtn.querySelector('i').replaceWith(createIconElement('x-circle', 'text-rose-500'));

                feedback.className = "p-4 rounded-2xl text-center font-bold text-sm bg-rose-100 text-rose-800 border border-rose-200";
                feedback.innerText = `Noto'g'ri. To'g'ri javob: ${correct}`;
            }

            feedback.classList.remove('hidden');

            setTimeout(() => {
                currentQuizIndex = (currentQuizIndex + 1) % wordsData.length;
                showQuizQuestion();
            }, 2000);
        }

        function createIconElement(name, colorClass) {
            const i = document.createElement('i');
            i.setAttribute('data-lucide', name);
            i.className = `w-5 h-5 ${colorClass}`;
            return i;
        }

        // --- MATCHING GAME LOGIC ---
        function startMatchingGame() {
            const grid = document.getElementById('matching-grid');
            grid.innerHTML = '';
            matchedPairsCount = 0;
            selectedMatchingWord = null;

            // Prepare English & Uzbek cards
            let items = [];
            wordsData.forEach((item, index) => {
                items.push({ id: index, text: item.word, lang: 'en' });
                items.push({ id: index, text: item.translation, lang: 'uz' });
            });

            // Shuffle cards
            items.sort(() => Math.random() - 0.5);

            items.forEach(item => {
                const card = document.createElement('button');
                card.className = "p-5 bg-white border border-slate-200 rounded-2xl shadow-sm text-center font-bold text-slate-700 hover:border-indigo-500 hover:bg-indigo-50/30 transition-all";
                card.innerText = item.text;
                card.dataset.id = item.id;
                card.dataset.lang = item.lang;

                card.onclick = () => handleMatchingClick(card);
                grid.appendChild(card);
            });
        }

        function handleMatchingClick(card) {
            if (card.classList.contains('matched') || card === selectedMatchingWord) return;

            if (!selectedMatchingWord) {
                // First card selection
                selectedMatchingWord = card;
                card.classList.add('border-indigo-600', 'bg-indigo-100/50', 'text-indigo-700');
            } else {
                // Second card selection
                const prevCard = selectedMatchingWord;

                if (prevCard.dataset.id === card.dataset.id && prevCard.dataset.lang !== card.dataset.lang) {
                    // Match found!
                    card.className = "p-5 bg-emerald-50 border-2 border-emerald-500 text-emerald-700 rounded-2xl font-bold matched cursor-default";
                    prevCard.className = "p-5 bg-emerald-50 border-2 border-emerald-500 text-emerald-700 rounded-2xl font-bold matched cursor-default";

                    score += 15;
                    updateScoreDisplay();
                    matchedPairsCount++;

                    if (matchedPairsCount === wordsData.length) {
                        setTimeout(() => {
                            alert("Barcha juftliklarni topdingiz! Barakalla 🎉");
                            startMatchingGame();
                        }, 500);
                    }
                } else {
                    // Not a match
                    card.classList.add('border-rose-500', 'bg-rose-50');
                    prevCard.classList.add('border-rose-500', 'bg-rose-50');

                    setTimeout(() => {
                        card.className = "p-5 bg-white border border-slate-200 rounded-2xl shadow-sm text-center font-bold text-slate-700 hover:border-indigo-500 transition-all";
                        prevCard.className = "p-5 bg-white border border-slate-200 rounded-2xl shadow-sm text-center font-bold text-slate-700 hover:border-indigo-500 transition-all";
                    }, 800);
                }

                selectedMatchingWord = null;
            }
        }

        function updateScoreDisplay() {
            document.getElementById('score-display').innerText = score;
        }

        // Initialize First Card
        updateCardDisplay();
    </script>
</body>
</html>
