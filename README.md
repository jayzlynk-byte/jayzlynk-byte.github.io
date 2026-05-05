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
