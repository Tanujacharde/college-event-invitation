<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College Event Invitation</title>

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
</head>

<body class="bg-gray-100 min-h-screen flex items-center justify-center p-6">

    <!-- Invitation Card -->
    <div class="max-w-3xl w-full bg-white rounded-2xl shadow-2xl overflow-hidden border border-gray-200">

        <!-- Header -->
        <div class="bg-blue-700 text-white text-center px-6 py-10">
            <p class="text-sm uppercase tracking-widest font-semibold">
                You Are Invited
            </p>

            <h1 class="text-4xl md:text-5xl font-bold mt-3">
                College Annual Event
            </h1>

            <p class="text-blue-100 mt-3 text-lg">
                Celebrate • Connect • Create Memories
            </p>
        </div>

        <!-- Event Details -->
        <div class="p-8">

            <div class="text-center">
                <h2 class="text-2xl font-bold text-gray-800">
                    Annual Cultural Fest 2026
                </h2>

                <p class="text-gray-600 mt-3 leading-relaxed">
                    Our college is delighted to invite you to the Annual Cultural
                    Fest. Join us for an exciting day filled with music, dance,
                    talent, fun and unforgettable memories.
                </p>
            </div>

            <!-- Details Grid -->
            <div class="grid md:grid-cols-3 gap-5 mt-8">

                <div class="border border-blue-200 rounded-xl p-5 text-center bg-blue-50">
                    <h3 class="font-bold text-blue-700 text-lg">Date</h3>
                    <p class="text-gray-700 mt-2">20 October 2026</p>
                </div>

                <div class="border border-blue-200 rounded-xl p-5 text-center bg-blue-50">
                    <h3 class="font-bold text-blue-700 text-lg">Time</h3>
                    <p class="text-gray-700 mt-2">10:00 AM onwards</p>
                </div>

                <div class="border border-blue-200 rounded-xl p-5 text-center bg-blue-50">
                    <h3 class="font-bold text-blue-700 text-lg">Venue</h3>
                    <p class="text-gray-700 mt-2">College Auditorium</p>
                </div>

            </div>

            <!-- Highlights -->
            <div class="mt-8 border-t border-gray-200 pt-6">
                <h3 class="text-xl font-bold text-gray-800 text-center">
                    Event Highlights
                </h3>

                <div class="flex flex-wrap justify-center gap-3 mt-4">
                    <span class="px-4 py-2 bg-purple-100 text-purple-700 rounded-full font-medium">
                        Dance
                    </span>

                    <span class="px-4 py-2 bg-pink-100 text-pink-700 rounded-full font-medium">
                        Music
                    </span>

                    <span class="px-4 py-2 bg-green-100 text-green-700 rounded-full font-medium">
                        Games
                    </span>

                    <span class="px-4 py-2 bg-yellow-100 text-yellow-700 rounded-full font-medium">
                        Food
                    </span>
                </div>
            </div>

            <!-- Invitation Message -->
            <div class="mt-8 text-center">
                <p class="text-gray-600">
                    Your presence will make this celebration even more special!
                </p>

                <!-- Button -->
                <button
                    class="mt-6 bg-blue-700 hover:bg-blue-800 text-white
                           font-semibold px-8 py-3 rounded-lg
                           shadow-md hover:shadow-lg transition duration-300">
                    RSVP Now
                </button>
            </div>

        </div>

        <!-- Footer -->
        <div class="bg-gray-900 text-gray-300 text-center py-5">
            <p class="font-semibold">S.B. Jain Institute of Technology</p>
            <p class="text-sm mt-1">
                Electronics & Telecommunication Department
            </p>
        </div>

    </div>

</body>
</html>
