[wearing.html](https://github.com/user-attachments/files/27392494/wearing.html)[types.html](https://github.com/user-attachments/files/27392484/types.html)[index.html](https://github.com/user-attachments/files/27392472/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Na Lei o Hawai'i | Home</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400..700;1,400..700&family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
    <!-- Custom Stylesheet -->
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Video Cover Styles */
        .video-cover-link {
            transition: transform 0.3s ease;
            display: block;
        }
        .video-cover-link:hover {
            transform: scale(1.02);
        }
        .play-button-overlay {
            background: rgba(255, 255, 255, 0.9);
            transition: background 0.3s ease;
        }
        .video-cover-link:hover .play-button-overlay {
            background: #ffcf40; /* Plumeria Yellow */
        }

        /* Interactive Card Animations */
        .interactive-card {
            transition: transform 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275), box-shadow 0.3s ease;
            cursor: pointer;
        }
        .interactive-card:hover {
            transform: translateY(-15px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.15) !important;
        }
        .interactive-card img {
            height: 200px;
            object-fit: cover;
        }
    </style>
</head>
<body>

    <!-- Requirement: Proper Navigation -->
    <nav class="navbar navbar-expand-lg sticky-top">
        <div class="container">
            <a class="navbar-brand fw-bold" href="index.html">Na Lei o Hawai'i</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link active" href="index.html">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="history.html">History</a></li>
                    <li class="nav-item"><a class="nav-link" href="types.html">Types</a></li>
                    <li class="nav-item"><a class="nav-link" href="process.html">Process</a></li>
                    <li class="nav-item"><a class="nav-link" href="wearing.html">Placement</a></li>
                    <li class="nav-item"><a class="nav-link" href="gallery.html">Gallery</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <main class="container my-5">
        <header class="text-center mb-5">
            <h1 class="display-3 fw-bold">The Breath of Aloha</h1>
            <p class="lead">Exploring the Art, Tradition, and Heart of Hawaiian Lei Making.</p>
        </header>

        <!-- Welcome Section -->
        <section class="row align-items-center g-5 mb-5">
            <div class="col-lg-6">
                <h2 class="mb-4">Welina Mai (Welcome)</h2>
                <p>In Hawai'i, the lei is a profound symbol of affection, honor, and celebration. Whether crafted from fragrant blossoms, sturdy leaves, or delicate shells, every lei tells a story of the relationship between the maker, the wearer, and the natural world.</p>
                <p>This digital portfolio is dedicated to preserving and sharing the intricate techniques of lei making. From the ancient protocols of gathering materials to modern-day celebrations, we invite you to explore the beauty of this living tradition.</p>
                <a href="process.html" class="btn btn-dark mt-3" style="background-color: var(--forest-green); border: none; padding: 10px 25px; border-radius: 50px;">Learn the Craft</a>
            </div>

            <div class="col-lg-6">
                <div class="ratio ratio-16x9 shadow-lg rounded overflow-hidden position-relative">
                    <!-- Added text-decoration-none to fix the blue link issue -->
                    <a href="https://www.youtube.com/watch?v=IwiUGgr0nK0" target="_blank" class="video-cover-link w-100 h-100 text-decoration-none">
                        <img src="images/home/video-thumbnail.jpeg" class="w-100 h-100 object-fit-cover" alt="The Ancient Art of Hawaiian Lei-making">
                        <div class="position-absolute top-50 start-50 translate-middle">
                            <div class="play-button-overlay rounded-circle p-4 shadow-lg">
                                <svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" fill="#2d4c3b" class="bi bi-play-fill" viewBox="0 0 16 16">
                                    <path d="m11.596 8.697-6.363 3.692c-.54.313-1.233-.066-1.233-.697V4.308c0-.63.692-1.01 1.233-.696l6.363 3.692a.802.802 0 0 1 0 1.393z"/>
                                </svg>
                            </div>
                        </div>
                    </a>
                </div>
                <p class="text-center mt-3 fst-italic text-muted small">Click to watch: The beautiful process of traditional lei making on YouTube.</p>
            </div>
        </section>

        <hr class="my-5">

        <!-- Interactive Lei Materials Grid -->
        <section class="my-5">
            <h2 class="text-center mb-2">The Elements of a Lei</h2>
            <p class="text-center text-muted mb-5">Hover over each material to learn more about its significance.</p>
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="card h-100 border-0 shadow-sm interactive-card">
                        <img src="images/home/puakenikeni.jpeg" class="card-img-top rounded-top" alt="Pua Kenikeni">
                        <div class="card-body text-center">
                            <h5 class="card-title fw-bold">Puakenikeni</h5>
                            <p class="card-text small text-muted">A fragrant favorite often used in kui style lei and known for its changing colors from white to orange.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card h-100 border-0 shadow-sm interactive-card">
                        <img src="images/home/laitileaf.jpeg" class="card-img-top rounded-top" alt="Ti Leaf">
                        <div class="card-body text-center">
                            <h5 class="card-title fw-bold">Lāʻī (Ti Leaf)</h5>
                            <p class="card-text small text-muted">Symbolizing protection and healing, these sturdy leaves are the foundation of many traditional leis.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card h-100 border-0 shadow-sm interactive-card">
                        <img src="images/home/ohialehua.jpeg" class="card-img-top rounded-top" alt="Lehua">
                        <div class="card-body text-center">
                            <h5 class="card-title fw-bold">ʻŌhiʻa Lehua</h5>
                            <p class="card-text small text-muted">The sacred flower of the island; gathering these requires deep respect for the 'āina and its legends.</p>
                        </div>
                    </div>
                </div>
<div class="col-md-4">
    <div class="card h-100 border-0 shadow-sm interactive-card">
        <img src="images/home/plumeria.jpeg" class="card-img-top rounded-top" alt="Plumeria">
        <div class="card-body text-center">
            <h5 class="card-title fw-bold">Plumeria</h5>
            <p class="card-text small text-muted">A delicate, star-shaped bloom known for its light, lemon-like fragrance and beautiful yellow-green hue. Plumerias come in a variety of colors.</p>
        </div>
    </div>
</div>
<div class="col-md-4">
    <div class="card h-100 border-0 shadow-sm interactive-card">
        <img src="images/home/maile.jpeg" class="card-img-top rounded-top" alt="Maile">
        <div class="card-body text-center">
            <h5 class="card-title fw-bold">Maile</h5>
            <p class="card-text small text-muted">One of the most sacred lei materials, these leafy vines represent honor and are traditionally used for milestones such as weddings and graduation.</p>
        </div>
    </div>
</div>
<div class="col-md-4">
    <div class="card h-100 border-0 shadow-sm interactive-card">
        <img src="images/home/kukui.jpeg" class="card-img-top rounded-top" alt="Kukui">
        <div class="card-body text-center">
            <h5 class="card-title fw-bold">Kukui (Candlenut)</h5>
            <p class="card-text small text-muted">Symbolizing light and wisdom, polished kukui nuts create a lasting lei that serves as a permanent keepsake.</p>
        </div>
    </div>
</div>


            </div>
        </section>
    </main>

    <!-- Floating Back to Top Button -->
    <button onclick="topFunction()" id="backToTop" title="Go to top" class="btn shadow-lg" style="display: none; position: fixed; bottom: 20px; right: 30px; z-index: 99; border-radius: 50%; width: 50px; height: 50px; background-color: #2d4c3b; color: white;">
        ↑
    </button>

    <footer class="py-5 text-center mt-5" style="background: var(--deep-bark); color: var(--sand-beige);">
        <div class="container">
            <p class="mb-1">&copy; 2026 Hawaiian Lei Making Project</p>
            <p class="small opacity-75">University of Hawai'i at Hilo | Web Design Final Submission</p>
        </div>
    </footer>

    <!-- Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

    <script>
        // Back to Top Logic
        let mybutton = document.getElementById("backToTop");
        window.onscroll = function() {scrollFunction()};

        function scrollFunction() {
            if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
                mybutton.style.display = "block";
            } else {
                mybutton.style.display = "none";
            }
        }

        function topFunction() {
            window.scrollTo({top: 0, behavior: 'smooth'});
        }
    </script>
</body>
</html>
[history.html](https://github.com/user-attachments/files/27392475/history.html)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>History | Na Lei o Hawai'i</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400..700;1,400..700&family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
    <!-- Your Global CSS -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Consistent Navigation -->
    <nav class="navbar navbar-expand-lg sticky-top">
        <div class="container">
            <a class="navbar-brand fw-bold" href="index.html">Na Lei o Hawai'i</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
                    <!-- Set as active for this page -->
                    <li class="nav-item"><a class="nav-link active" href="history.html">History</a></li>
                    <li class="nav-item"><a class="nav-link" href="types.html">Types</a></li>
                    <li class="nav-item"><a class="nav-link" href="process.html">Process</a></li>
                    <li class="nav-item"><a class="nav-link" href="wearing.html">Placement</a></li>
                    <li class="nav-item"><a class="nav-link" href="gallery.html">Gallery</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <main class="container my-5">
        <header class="text-center mb-5">
            <h1 class="display-4">The Legacy of the Lei</h1>
            <p class="lead">Tracing the tradition from ancient voyagers to modern celebrations.</p>
        </header>

        <!-- Section 1: Ancient Origins -->
        <article class="row align-items-center mb-5">
            <div class="col-md-6 order-md-2">
                <img src="images/history/ancientorigins.jpeg" class="img-fluid rounded shadow" alt="Ancient Hawaiian lei materials">
            </div>
            <div class="col-md-6 order-md-1">
                <h2 class="h3 text-success">Ancient Origins</h2>
                <p>The tradition of lei making arrived in the islands with the first Polynesian voyagers. In ancient Hawai'i, these garlands were far more than simple decoration; they were symbols of rank, spiritual protection, and sacred offerings to the gods. Materials were gathered with deep respect for the 'āina (land), using native plants like maile, lehua, and hala.</p>
            </div>
        </article>

        <!-- Section 2: The Golden Age of the Monarchy -->
        <article class="row align-items-center mb-5">
            <div class="col-md-6">
                <img src="images/history/monarchydiplomacy.jpeg" class="img-fluid rounded shadow" alt="Hawaiian royalty wearing lei">
            </div>
            <div class="col-md-6">
                <h2 class="h3 text-success">The Monarchy & Diplomacy</h2>
                <p>During the era of the Hawaiian Kingdom, the lei became a central part of royal protocol. Ali'i (royalty) often wore exquisite lei made of feathers or rare shells to signify their status. The lei also served as a tool for diplomacy, gifted to visiting dignitaries as a sign of peace and shared aloha.</p>
            </div>
        </article>

        <!-- Section 3: Modern Lei Day -->
        <article class="row align-items-center">
            <div class="col-md-6 order-md-2">
                <img src="images/history/maydayisleiday.jpeg" class="img-fluid rounded shadow" alt="Modern Lei Day celebration">
            </div>
            <div class="col-md-6 order-md-1">
                <h2 class="h3 text-success">May Day is Lei Day</h2>
                <p>In 1927, writer Don Blanding and columnist Grace Tower Warren proposed a day dedicated specifically to the lei. This led to the first "Lei Day" celebration on May 1, 1928. Today, it remains a beloved tradition across the islands, featuring competitions that showcase the incredible artistry and technical skill of local lei makers.</p>
            </div>
        </article>
    </main>

    <!-- NEW: Floating Back to Top Button -->
    <button onclick="topFunction()" id="backToTop" title="Go to top" class="btn shadow-lg">
        ↑
    </button>

    <footer class="py-4 text-center mt-5" style="background: var(--deep-bark); color: white;">
        <p>&copy; 2026 Hawaiian Lei Making Project | UH Hilo Final Submission</p>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

    <!-- NEW: Back to Top Script -->
    <script>
        let mybutton = document.getElementById("backToTop");

        window.onscroll = function() {scrollFunction()};

        function scrollFunction() {
            if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
                mybutton.style.display = "block";
            } else {
                mybutton.style.display = "none";
            }
        }

        function topFunction() {
            window.scrollTo({top: 0, behavior: 'smooth'});
        }
    </script>
</body>
</html>

[Uploading <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lei Methods | Na Lei o Hawai'i</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400..700;1,400..700&family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Requirement: Consistent Navigation -->
    <nav class="navbar navbar-expand-lg sticky-top">
        <div class="container">
            <a class="navbar-brand fw-bold" href="index.html">Na Lei o Hawai'i</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="history.html">History</a></li>
                    <li class="nav-item"><a class="nav-link active" href="types.html">Types</a></li>
                    <li class="nav-item"><a class="nav-link" href="process.html">Process</a></li>
                    <li class="nav-item"><a class="nav-link" href="wearing.html">Placement</a></li>
                    <li class="nav-item"><a class="nav-link" href="gallery.html">Gallery</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <main class="container my-5">
        <header class="text-center mb-5">
            <h1 class="display-4">The Eight Methods of Lei Construction</h1>
            <p class="lead text-muted">The unique handiwork that gives each lei its character and form.</p>
        </header>

        <!-- Row 1: First 6 Methods (3 per row on large screens) -->
        <div class="row g-4">
            <!-- Hilo -->
            <div class="col-md-6 col-lg-4">
                <div class="card h-100 border-0 shadow-sm interactive-card">
                    <img src="images/lei-methods/type-hilo.jpeg" class="card-img-top" alt="Hilo Method">
                    <div class="card-body">
                        <h3 class="h5 text-success">Hilo</h3>
                        <p class="card-text">A twisting method where two strands are twisted together to form a rope, most commonly used with ti leaves.</p>
                    </div>
                </div>
            </div>

            <!-- Haku -->
            <div class="col-md-6 col-lg-4">
                <div class="card h-100 border-0 shadow-sm interactive-card">
                    <img src="images/lei-methods/type-haku.jpeg" class="card-img-top" alt="Haku Method">
                    <div class="card-body">
                        <h3 class="h5 text-success">Haku</h3>
                        <p class="card-text">A braiding technique where three or more strands of backing material are braided while decorative elements are tucked in.</p>
                    </div>
                </div>
            </div>

            <!-- Hīpu'upu'u -->
            <div class="col-md-6 col-lg-4">
                <div class="card h-100 border-0 shadow-sm interactive-card">
                    <img src="images/lei-methods/type-hipuupuu.jpeg" class="card-img-top" alt="Hīpu'upu'u Method">
                    <div class="card-body">
                        <h3 class="h5 text-success">Hīpu'upu'u</h3>
                        <p class="card-text">A method where the stems of the plant material are knotted together to form a chain.</p>
                    </div>
                </div>
            </div>

            <!-- Humuhumu -->
            <div class="col-md-6 col-lg-4">
                <div class="card h-100 border-0 shadow-sm interactive-card">
                    <img src="images/lei-methods/type-humuhumu.jpeg" class="card-img-top" alt="Humuhumu Method">
                    <div class="card-body">
                        <h3 class="h5 text-success">Humuhumu</h3>
                        <p class="card-text">A sewing method where the decorative materials are sewn directly onto a backing, such as felt or dried banana fiber.</p>
                    </div>
                </div>
            </div>

            <!-- Hili -->
            <div class="col-md-6 col-lg-4">
                <div class="card h-100 border-0 shadow-sm interactive-card">
                    <img src="images/lei-methods/type-hili.jpeg" class="card-img-top" alt="Hili Method">
                    <div class="card-body">
                        <h3 class="h5 text-success">Hili</h3>
                        <p class="card-text">A technique involving the braiding or plaiting of a single type of material, usually a vine or long-stemmed plant.</p>
                    </div>
                </div>
            </div>

            <!-- Kui -->
            <div class="col-md-6 col-lg-4">
                <div class="card h-100 border-0 shadow-sm interactive-card">
                    <img src="images/lei-methods/type-kui.jpeg" class="card-img-top" alt="Kui Method">
                    <div class="card-body">
                        <h3 class="h5 text-success">Kui</h3>
                        <p class="card-text">The most common piercing method using a needle and thread to string flowers together.</p>
                    </div>
                </div>
            </div>
        </div>

        <!-- Row 2: Final 2 Methods centered to avoid empty space -->
        <div class="row g-4 justify-content-center mt-2">
            <!-- Wili -->
            <div class="col-md-6 col-lg-4">
                <div class="card h-100 border-0 shadow-sm interactive-card">
                    <img src="images/lei-methods/type-wili.jpeg" class="card-img-top" alt="Wili Method">
                    <div class="card-body">
                        <h3 class="h5 text-success">Wili</h3>
                        <p class="card-text">A corkscrew or winding method where fiber is wrapped around a central core of material.</p>
                    </div>
                </div>
            </div>

            <!-- Nīki'i -->
            <div class="col-md-6 col-lg-4">
                <div class="card h-100 border-0 shadow-sm interactive-card">
                    <img src="images/lei-methods/type-nikii.jpeg" class="card-img-top" alt="Nīki'i Method">
                    <div class="card-body">
                        <h3 class="h5 text-success">Nīki'i</h3>
                        <p class="card-text">A technique that involves tying or knotting separate pieces of material onto a main cord.</p>
                    </div>
                </div>
            </div>
        </div>
    </main>

    <!-- Floating Back to Top Button -->
    <button onclick="topFunction()" id="backToTop" title="Go to top" class="btn shadow-lg">
        ↑
    </button>

    <footer class="py-4 text-center mt-5" style="background: var(--deep-bark); color: white;">
        <p>&copy; 2026 Hawaiian Lei Making Project | University of Hawai'i at Hilo</p>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

    <!-- Back to Top Script -->
    <script>
        let mybutton = document.getElementById("backToTop");
        window.onscroll = function() {scrollFunction()};

        function scrollFunction() {
            if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
                mybutton.style.display = "block";
            } else {
                mybutton.style.display = "none";
            }
        }

        function topFunction() {
            window.scrollTo({top: 0, behavior: 'smooth'});
        }
    </script>
</body>
</html>

[process.html](https://github.com/user-attachments/files/27392491/process.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Process | Na Lei o Hawai'i</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400..700;1,400..700&family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Custom styles to match Screenshot 2026-05-04 at 1.40.04 AM.png */
        .lei-maker-title {
            color: #2d5842;
            font-family: 'Lora', serif;
            font-weight: bold;
        }
        .btn-submit-custom {
            background-color: #2d5842;
            border: none;
            color: white;
            padding: 12px;
            font-size: 1.2rem;
            border-radius: 8px;
        }
        .btn-submit-custom:hover {
            background-color: #214131;
            color: white;
        }
    </style>
</head>
<body>

    <!-- Consistent Navigation -->
    <nav class="navbar navbar-expand-lg sticky-top">
        <div class="container">
            <a class="navbar-brand fw-bold" href="index.html">Na Lei o Hawai'i</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="history.html">History</a></li>
                    <li class="nav-item"><a class="nav-link" href="types.html">Types</a></li>
                    <!-- Set as active for this page -->
                    <li class="nav-item"><a class="nav-link active" href="process.html">Process</a></li>
                    <li class="nav-item"><a class="nav-link" href="wearing.html">Placement</a></li>
                    <li class="nav-item"><a class="nav-link" href="gallery.html">Gallery</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <main class="container my-5">
        <header class="text-center mb-5">
            <h1 class="display-4">The Art of the Craft</h1>
            <p class="lead">A sacred journey from the 'āina to the final knot.</p>
        </header>

        <!-- Section 1: Gathering and Preparation -->
        <div class="row mb-5">
            <div class="col-md-6 mb-4">
                <h2 class="h4 text-success border-bottom pb-2">1. Gathering ('Ohina)</h2>
                <ul class="list-group list-group-flush shadow-sm rounded">
                    <li class="list-group-item"><strong>Selective Harvesting:</strong> Practitioners only take what is needed, ensuring the plant remains healthy for future growth.</li>
                    <li class="list-group-item"><strong>Timing:</strong> Materials are recommended to be gathered early in the morning while dew is present to maintain freshness. However, any time during the day is okay. Night time picking is usually not recommended due to ancient myths, plant vitality, and safety.</li>
                    <li class="list-group-item"><strong>Variety:</strong> Includes flowers (pua), leaves (lau), or vines (maile) depending on the intent.</li>
                </ul>
            </div>
            <div class="col-md-6 mb-4">
                <h2 class="h4 text-success border-bottom pb-2">2. Preparation</h2>
                <ul class="list-group list-group-flush shadow-sm rounded">
                    <li class="list-group-item"><strong>Cleaning:</strong> Be delicate and gentle when cleaning materials, especially flowers, to prevent bruising and loss of fragrance.</li>
                    <li class="list-group-item"><strong>Drying:</strong> Gently dab dry or air dry; avoid drying too long so flowers don't die quickly.</li>
                    <li class="list-group-item"><strong>Sorting:</strong> Organize by size and color before constructing to stay organized.</li>
                    <li class="list-group-item bg-light"><strong>Pro-Tip:</strong> Maintain a positive mind and spirit. Lei making is a mental craft; your lei feeds off your energy.</li>
                </ul>
            </div>
        </div>

        <!-- Section 2: Construction Table -->
        <section class="mb-5">
            <h2 class="h4 text-success mb-4">3. Construction Methods</h2>
            <div class="table-responsive shadow-sm rounded">
                <table class="table table-hover align-middle mb-0" style="background: white;">
                    <thead class="table-dark">
                        <tr>
                            <th scope="col">Method</th>
                            <th scope="col">Technique Description</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr><td><strong>Kui</strong></td><td>The most common piercing method; uses a needle and thread to string flowers together.</td></tr>
                        <tr><td><strong>Hilo</strong></td><td>A twisting method using two strands to form a rope; common with ti leaves.</td></tr>
                        <tr><td><strong>Wili</strong></td><td>A winding method where fiber wraps around a central core to secure elements.</td></tr>
                        <tr><td><strong>Haku</strong></td><td>A braiding technique where elements are tucked into three or more strands of backing.</td></tr>
                        <tr><td><strong>Hīpu’upu’u</strong></td><td>Method where stems of plant material are knotted together to create a chain.</td></tr>
                        <tr><td><strong>Humuhumu</strong></td><td>Sewing technique where materials are sewn directly onto a backing like felt.</td></tr>
                        <tr><td><strong>Hili</strong></td><td>Braiding or plaiting of a single type of material, typically a vine or long-stemmed plant.</td></tr>
                        <tr><td><strong>Nīki’i</strong></td><td>Tying or knotting separate pieces, mainly Ni’ihau shells, onto a main cord.</td></tr>
                    </tbody>
                </table>
            </div>
        </section>

        <!-- Section 3: Finishing -->
        <div class="p-4 bg-light rounded border-start border-4 border-success mb-5">
            <h2 class="h4">4. Finishing and Storage</h2>
            <p>Once secured, mist with water and store in a cool, sealed container. Be mindful as some flowers and ferns brown quickly if they get too wet.</p>
        </div>

        <!-- Inquiry Form -->
        <section class="row justify-content-center mb-5">
            <div class="col-lg-10">
                <div class="card shadow border-0 p-4">
                    <div class="card-body">
                        <h2 class="text-center mb-4 lei-maker-title">Lei Maker's Inquiry</h2>
                        <form id="processForm">
                            <div class="row mb-3">
                                <div class="col-md-6">
                                    <label class="form-label fw-bold">Your Name</label>
                                    <input type="text" id="visitorName" class="form-control" required>
                                </div>
                                <div class="col-md-6">
                                    <label class="form-label fw-bold">Email</label>
                                    <input type="email" class="form-control" required>
                                </div>
                            </div>
                            <div class="mb-3">
                                <label class="form-label fw-bold">Select a Method</label>
                                <select class="form-select" id="methodSelect">
                                    <option value="Hilo">Hilo</option>
                                    <option value="Haku">Haku</option>
                                    <option value="Kui">Kui</option>
                                    <option value="Wili">Wili</option>
                                    <option value="Humuhumu">Humuhumu</option>
                                    <option value="Hīpu’upu’u">Hīpu’upu’u</option>
                                    <option value="Hili">Hili</option>
                                    <option value="Nīki’i">Nīki’i</option>
                                    <option value="Other">Other</option>
                                </select>
                            </div>
                            <div class="mb-4">
                                <label class="form-label fw-bold">Your Question</label>
                                <textarea class="form-control" rows="6" required></textarea>
                            </div>
                            <div class="d-grid">
                                <button type="submit" class="btn btn-submit-custom">Submit Inquiry</button>
                            </div>
                        </form>
                        <div id="formSuccess" class="mt-4 alert alert-success d-none text-center" role="alert">
                            <h4 class="alert-heading">Mahalo!</h4>
                            <p id="successMessage"></p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- NEW: Floating Back to Top Button -->
    <button onclick="topFunction()" id="backToTop" title="Go to top" class="btn shadow-lg">
        ↑
    </button>

    <footer class="py-4 text-center mt-5" style="background: var(--deep-bark); color: white;">
        <p>&copy; 2026 Hawaiian Lei Making Project | UH Hilo Final Submission</p>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

    <!-- Form Handling and Back to Top Script -->
    <script>
        // Form logic
        document.getElementById('processForm').addEventListener('submit', function(event) {
            event.preventDefault();
            const name = document.getElementById('visitorName').value;
            const method = document.getElementById('methodSelect').value;
            const successDiv = document.getElementById('formSuccess');
            const messageP = document.getElementById('successMessage');
            messageP.innerText = "Mahalo, " + name + "! We have received your question regarding the " + method + " method.";
            successDiv.classList.remove('d-none');
            this.classList.add('d-none');
        });

        // Back to top logic
        let mybutton = document.getElementById("backToTop");
        window.onscroll = function() {scrollFunction()};

        function scrollFunction() {
            if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
                mybutton.style.display = "block";
            } else {
                mybutton.style.display = "none";
            }
        }

        function topFunction() {
            window.scrollTo({top: 0, behavior: 'smooth'});
        }
    </script>
</body>
</html>

[Upl<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wearing Lei | Na Lei o Hawai'i</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400..700;1,400..700&family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
    <style>
        .wearing-card {
            border: none;
            transition: transform 0.3s ease;
            overflow: hidden;
            background: white;
        }
        .wearing-card:hover {
            transform: translateY(-5px);
        }
        .term-title {
            color: #2d5842;
            font-family: 'Lora', serif;
            font-weight: bold;
        }
        .wearing-img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-bottom: 4px solid #2d5842;
        }

        /* Back to Top Button Styling */
        #backToTop {
            display: none;
            position: fixed;
            bottom: 20px;
            right: 30px;
            z-index: 99;
            font-size: 18px;
            border: none;
            outline: none;
            background-color: #2d5842;
            color: white;
            cursor: pointer;
            padding: 15px;
            border-radius: 50%;
            width: 50px;
            height: 50px;
            line-height: 20px;
            text-align: center;
        }

        #backToTop:hover {
            background-color: #214131;
        }
    </style>
</head>
<body>

    <!-- Consistent Navigation -->
    <nav class="navbar navbar-expand-lg sticky-top">
        <div class="container">
            <a class="navbar-brand fw-bold" href="index.html">Na Lei o Hawai'i</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="history.html">History</a></li>
                    <li class="nav-item"><a class="nav-link" href="types.html">Types</a></li>
                    <li class="nav-item"><a class="nav-link" href="process.html">Process</a></li>
                    <li class="nav-item"><a class="nav-link active" href="wearing.html">Placement</a></li>
                    <li class="nav-item"><a class="nav-link" href="gallery.html">Gallery</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <main class="container my-5">
        <header class="text-center mb-5">
            <h1 class="display-4">Names & Placement</h1>
            <p class="lead">A lei is named not just for its materials, but for where it is worn on the body.</p>
        </header>

        <div class="row g-4">
            <!-- Lei Po'o -->
            <div class="col-md-6">
                <article class="card h-100 shadow-sm wearing-card">
                    <img src="images/wearing/leipoo.jpeg" class="wearing-img" alt="Lei Po'o worn on the head">
                    <div class="card-body">
                        <h2 class="h4 term-title">Lei Po'o</h2>
                        <p class="text-muted fst-italic">"Po'o" means head.</p>
                        <p>This is a lei worn specifically on the head. While many people refer to these as "haku lei," haku refers to the braiding method, whereas Lei Po'o refers to the placement. These are common for hula dancers, brides, and special celebrations.</p>
                    </div>
                </article>
            </div>

            <!-- Lei ʻĀʻī -->
            <div class="col-md-6">
                <article class="card h-100 shadow-sm wearing-card">
                    <img src="images/wearing/leiai.jpeg" class="wearing-img" alt="Lei ʻĀʻī worn around the neck">
                    <div class="card-body">
                        <h2 class="h4 term-title">Lei ʻĀʻī</h2>
                        <p class="text-muted fst-italic">"ʻĀʻī" means neck.</p>
                        <p>This is the most recognizable form of lei, worn around the neck. Traditionally, it should drape evenly over the shoulders. It is a symbol of affection, welcome, or honor and is the standard style for graduations and greetings.</p>
                    </div>
                </article>
            </div>

            <!-- Kupe'e -->
            <div class="col-md-6">
                <article class="card h-100 shadow-sm wearing-card">
                    <img src="images/wearing/kupee.jpeg" class="wearing-img" alt="Kupe'e worn on wrists or ankles">
                    <div class="card-body">
                        <h2 class="h4 term-title">Kupe'e</h2>
                        <p class="text-muted fst-italic">Wrists or Ankles.</p>
                        <p>These are lei worn specifically around the wrists or ankles. In Hula, kupe'e are often made of greenery (like fern or ti leaf) and are used to draw attention to the movements of the hands and feet while also protecting the dancer.</p>
                    </div>
                </article>
            </div>

            <!-- Lei Pāpale -->
            <div class="col-md-6">
                <article class="card h-100 shadow-sm wearing-card">
                    <img src="images/wearing/leipapale.jpeg" class="wearing-img" alt="Lei Pāpale worn on a hat">
                    <div class="card-body">
                        <h2 class="h4 term-title">Lei Pāpale</h2>
                        <p class="text-muted fst-italic">"Pāpale" means hat.</p>
                        <p>This refers to a lei worn around a hat. This tradition is a beautiful way to decorate lauhala hats. The lei is typically sized specifically to fit the crown of the pāpale and is a favorite style for local festivities and parades.</p>
                    </div>
                </article>
            </div>
        </div>

        <!-- Extra Etiquette Section -->
        <section class="mt-5 p-4 bg-light rounded shadow-sm border-start border-4 border-success">
            <h3 class="h4 term-title mb-3">General Protocol</h3>
            <ul class="list-group list-group-flush">
                <li class="list-group-item bg-transparent">A lei should be worn draped over the shoulders, hanging down both in the front and the back.</li>
                <li class="list-group-item bg-transparent">It is considered disrespectful to refuse a lei that is offered with aloha.</li>
                <li class="list-group-item bg-transparent">Traditionally, a lei should never be thrown in the trash; when it is spent, it should be returned to the earth.</li>
            </ul>
        </section>
    </main>

    <!-- Floating Back to Top Button -->
    <button onclick="topFunction()" id="backToTop" title="Go to top">
        ↑
    </button>

    <footer class="py-4 text-center mt-5" style="background: var(--deep-bark); color: white;">
        <p>&copy; 2026 Hawaiian Lei Making Project | UH Hilo Final Submission</p>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

    <!-- Back to Top Script -->
    <script>
        // Get the button
        let mybutton = document.getElementById("backToTop");

        // Show button when user scrolls down 100px
        window.onscroll = function() {scrollFunction()};

        function scrollFunction() {
            if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
                mybutton.style.display = "block";
            } else {
                mybutton.style.display = "none";
            }
        }

        // Scroll to the top when the button is clicked
        function topFunction() {
            window.scrollTo({top: 0, behavior: 'smooth'});
        }
    </script>
</body>
</html>

[gallery.html](https://github.com/user-attachments/files/27392507/gallery.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery | Na Lei o Hawai'i</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400..700;1,400..700&family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
    <style>
        .gallery-card {
            position: relative;
            overflow: hidden;
            border-radius: 12px;
            cursor: pointer;
            height: 250px; 
        }
        .gallery-img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }
        .gallery-overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(45, 88, 66, 0.85); /* Forest Green */
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            opacity: 0;
            transition: opacity 0.4s ease;
            color: white;
            padding: 15px;
        }
        .gallery-card:hover .gallery-img { transform: scale(1.1); }
        .gallery-card:hover .gallery-overlay { opacity: 1; }
        
        /* Modal Polish */
        .modal-content { background: transparent; border: none; }
        .btn-close-white { filter: invert(1) grayscale(100%) brightness(200%); }

        /* Back to Top Button Styling */
        #backToTop {
            display: none;
            position: fixed;
            bottom: 20px;
            right: 30px;
            z-index: 99;
            font-size: 18px;
            border: none;
            outline: none;
            background-color: #2d5842;
            color: white;
            cursor: pointer;
            padding: 15px;
            border-radius: 50%;
            width: 50px;
            height: 50px;
            line-height: 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0,0,0,0.3);
        }

        #backToTop:hover {
            background-color: #214131;
        }
    </style>
</head>
<body>

    <nav class="navbar navbar-expand-lg sticky-top">
        <div class="container">
            <a class="navbar-brand fw-bold" href="index.html">Na Lei o Hawai'i</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="history.html">History</a></li>
                    <li class="nav-item"><a class="nav-link" href="types.html">Types</a></li>
                    <li class="nav-item"><a class="nav-link" href="process.html">Process</a></li>
                    <li class="nav-item"><a class="nav-link" href="wearing.html">Placement</a></li>
                    <!-- Set as active for this page -->
                    <li class="nav-item"><a class="nav-link active" href="gallery.html">Gallery</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <main class="container my-5">
        <header class="text-center mb-5">
            <h1 class="display-4">Visualizing Aloha</h1>
            <p class="lead">A comprehensive collection of Hawaiian lei artistry.</p>
        </header>

        <div class="row g-4">
            <!-- Row 1 -->
            <div class="col-sm-6 col-md-4 col-lg-3">
                <div class="gallery-card shadow" data-bs-toggle="modal" data-bs-target="#lightboxModal" data-img="images/gallery/plumeriakui.jpeg" data-caption="Traditional Plumeria Kui Lei">
                    <img src="images/gallery/plumeriakui.jpeg" class="gallery-img" alt="Plumeria Lei">
                    <div class="gallery-overlay"><h6 class="fw-bold">Plumeria</h6><p class="small">Kui Method</p></div>
                </div>
            </div>
            <div class="col-sm-6 col-md-4 col-lg-3">
                <div class="gallery-card shadow" data-bs-toggle="modal" data-bs-target="#lightboxModal" data-img="images/gallery/tileafhilo.jpeg" data-caption="Ti Leaf Hilo Lei">
                    <img src="images/gallery/tileafhilo.jpeg" class="gallery-img" alt="Ti Leaf Lei">
                    <div class="gallery-overlay"><h6 class="fw-bold">Ti Leaf</h6><p class="small">Hilo Method</p></div>
                </div>
            </div>
            <div class="col-sm-6 col-md-4 col-lg-3">
                <div class="gallery-card shadow" data-bs-toggle="modal" data-bs-target="#lightboxModal" data-img="images/gallery/mailewili.jpeg" data-caption="Maile Wili Lei">
                    <img src="images/gallery/mailewili.jpeg" class="gallery-img" alt="Maile Lei">
                    <div class="gallery-overlay"><h6 class="fw-bold">Maile</h6><p class="small">Wili Method</p></div>
                </div>
            </div>
            <div class="col-sm-6 col-md-4 col-lg-3">
                <div class="gallery-card shadow" data-bs-toggle="modal" data-bs-target="#lightboxModal" data-img="images/gallery/mixedfloralhaku.jpeg" data-caption="Mixed Floral Haku Lei">
                    <img src="images/gallery/mixedfloralhaku.jpeg" class="gallery-img" alt="Mixed Floral Lei">
                    <div class="gallery-overlay"><h6 class="fw-bold">Mixed Floral</h6><p class="small">Haku Method</p></div>
                </div>
            </div>

            <!-- Row 2 -->
            <div class="col-sm-6 col-md-4 col-lg-3">
                <div class="gallery-card shadow" data-bs-toggle="modal" data-bs-target="#lightboxModal" data-img="images/gallery/kukuihipuupuu.jpeg" data-caption="Kukui Hīpu’upu’u">
                    <img src="images/gallery/kukuihipuupuu.jpeg" class="gallery-img" alt="Kukui Leaf Lei">
                    <div class="gallery-overlay"><h6 class="fw-bold">Kukui Leaves</h6><p class="small">Hīpu’upu’u Method</p></div>
                </div>
            </div>
            <div class="col-sm-6 col-md-4 col-lg-3">
                <div class="gallery-card shadow" data-bs-toggle="modal" data-bs-target="#lightboxModal" data-img="images/gallery/yellowgrasshili.jpeg" data-caption=" Kauna’oa Pehu Hili Lei">
                    <img src="images/gallery/yellowgrasshili.jpeg" class="gallery-img" alt="Kauna’oa Pehu Lei">
                    <div class="gallery-overlay"><h6 class="fw-bold">Kauna’oa Pehu</h6><p class="small">Hili Method</p></div>
                </div>
            </div>
            <div class="col-sm-6 col-md-4 col-lg-3">
                <div class="gallery-card shadow" data-bs-toggle="modal" data-bs-target="#lightboxModal" data-img="images/gallery/featherhumuhumu.jpeg" data-caption="Flat Humuhumu Feather Lei">
                    <img src="images/gallery/featherhumuhumu.jpeg" class="gallery-img" alt="Feather Lei">
                    <div class="gallery-overlay"><h6 class="fw-bold">Feathers</h6><p class="small">Humuhumu Method</p></div>
                </div>
            </div>
            <div class="col-sm-6 col-md-4 col-lg-3">
                <div class="gallery-card shadow" data-bs-toggle="modal" data-bs-target="#lightboxModal" data-img="images/gallery/niihaunikii.jpeg" data-caption="Ni'ihau Shell Lei">
                    <img src="images/gallery/niihaunikii.jpeg" class="gallery-img" alt="Ni'ihau Shell Lei">
                    <div class="gallery-overlay"><h6 class="fw-bold">Ni'ihau Shells</h6><p class="small">Nīki’i Method</p></div>
                </div>
            </div>

            <!-- Row 3 -->
            <div class="col-sm-6 col-md-4 col-lg-3">
                <div class="gallery-card shadow" data-bs-toggle="modal" data-bs-target="#lightboxModal" data-img="images/gallery/kupeenikii.jpeg" data-caption="Kūpe’e Shell Lei">
                    <img src="images/gallery/kupeenikii.jpeg" class="gallery-img" alt="Kūpe’e Shell Lei">
                    <div class="gallery-overlay"><h6 class="fw-bold">Kūpe’e Shells</h6><p class="small">Nīki’i Method</p></div>
                </div>
            </div>
            <div class="col-sm-6 col-md-4 col-lg-3">
                <div class="gallery-card shadow" data-bs-toggle="modal" data-bs-target="#lightboxModal" data-img="images/gallery/poepoekui.jpeg" data-caption="Poepoe Plumeria">
                    <img src="images/gallery/poepoekui.jpeg" class="gallery-img" alt="Poepoe Plumeria Lei">
                    <div class="gallery-overlay"><h6 class="fw-bold">Plumeria</h6><p class="small">Kui Method</p></div>
                </div>
            </div>
            <div class="col-sm-6 col-md-4 col-lg-3">
                <div class="gallery-card shadow" data-bs-toggle="modal" data-bs-target="#lightboxModal" data-img="images/gallery/twistedkui.jpeg" data-caption="Four-strand Twisted Lei">
                    <img src="images/gallery/twistedkui.jpeg" class="gallery-img" alt="Twisted Mixed Floral Lei">
                    <div class="gallery-overlay"><h6 class="fw-bold">Roses, Pakalana, Pikake</h6><p class="small">Kui Method</p></div>
                </div>
            </div>
            <div class="col-sm-6 col-md-4 col-lg-3">
                <div class="gallery-card shadow" data-bs-toggle="modal" data-bs-target="#lightboxModal" data-img="images/gallery/hulumanuhumuhumu.jpeg" data-caption="Hulu Manu">
                    <img src="images/gallery/hulumanuhumuhumu.jpeg" class="gallery-img" alt="Hulu Manu Feather Lei">
                    <div class="gallery-overlay"><h6 class="fw-bold">Feathers</h6><p class="small">Humuhumu Method</p></div>
                </div>
            </div>
        </div>
    </main>

    <!-- Lightbox Modal -->
    <div class="modal fade" id="lightboxModal" tabindex="-1" aria-hidden="true">
        <div class="modal-dialog modal-dialog-centered modal-lg">
            <div class="modal-content">
                <div class="modal-body p-0 position-relative text-center">
                    <button type="button" class="btn-close btn-close-white position-absolute top-0 end-0 m-3" data-bs-dismiss="modal"></button>
                    <img src="" id="modalImg" class="img-fluid rounded shadow" alt="Full view">
                    <div class="bg-dark text-white p-3 rounded-bottom">
                        <p id="modalCaption" class="mb-0"></p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Floating Back to Top Button -->
    <button onclick="topFunction()" id="backToTop" title="Go to top">
        ↑
    </button>

    <footer class="py-4 text-center mt-5" style="background: var(--deep-bark); color: white;">
        <p>&copy; 2026 Hawaiian Lei Making Project | UH Hilo Final Submission</p>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

    <script>
        // Lightbox Logic
        const lightboxModal = document.getElementById('lightboxModal');
        lightboxModal.addEventListener('show.bs.modal', function (event) {
            const button = event.relatedTarget; 
            const imgSrc = button.getAttribute('data-img');
            const caption = button.getAttribute('data-caption');
            document.getElementById('modalImg').src = imgSrc;
            document.getElementById('modalCaption').innerText = caption;
        });

        // Back to Top Logic
        let mybutton = document.getElementById("backToTop");
        window.onscroll = function() {scrollFunction()};

        function scrollFunction() {
            if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
                mybutton.style.display = "block";
            } else {
                mybutton.style.display = "none";
            }
        }

        function topFunction() {
            window.scrollTo({top: 0, behavior: 'smooth'});
        }
    </script>
</body>
</html>





