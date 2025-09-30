<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proposal Template</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6;
            color: #1f2937;
        }
        canvas {
            border: 1px solid #d1d5db;
            border-radius: 0.5rem;
            background-color: #f9fafb;
            cursor: crosshair;
        }
    </style>
</head>
<body class="p-6 sm:p-10">

    <div id="proposal-content" class="max-w-4xl mx-auto bg-white rounded-lg shadow-xl p-6 sm:p-10">
        
        <header class="text-center mb-8">
            <h1 class="text-3xl sm:text-4xl font-bold text-gray-800">Holland Family Home Services, Inc.</h1>
            <p class="text-md sm:text-lg text-gray-600 mt-2">70 Copper Head Trail, Murphy, NC 828-541-2442 TheHollandSeven@gmail.com</p>
            <hr class="my-6 border-gray-300">
            <h2 class="text-2xl sm:text-3xl font-semibold text-gray-700">PROPOSAL FOR: Bathroom Renovation</h2>
        </header>

        <section class="prose max-w-none text-gray-700">
            <p class="mb-2"><strong>Client Name:</strong> Janice King / Kathrine Bass</p>
            <p class="mb-2"><strong>Project Address:</strong> 47 Cheerio LN, Murphy, NC, 28906</p>
            <p class="mb-6"><strong>Date of Issue:</strong> 2025-09-30</p>

            <h3 class="text-xl sm:text-2xl font-bold mt-8 mb-4">Project Objective & Scope</h3>
            <p class="mb-4">This proposal outlines a <strong>Guaranteed Maximum Price (GMP)</strong> for the full renovation of your existing bathroom. The objective is to convert the tub-and-shower combination to a walk-in shower, replace the toilet with a comfort-height unit, and replace the sink basin, faucet, and associated hardware. All materials will be sourced and supplied by the Contractor.</p>
            
            <h4 class="font-semibold text-lg mt-4">Total Material Allowance (All Projects)</h4>
            <p class="mb-6 border border-green-300 p-3 bg-green-50 rounded-md">
                This <strong>Fixed Allowance</strong> covers the cost of <strong>all</strong> fixtures, parts, installation supplies, sales tax, and the $125 delivery/disposal fee: <strong>$2,928.05</strong>
                <em class="block text-xs mt-1">*(A separate, itemized list of all included items is provided for your review.)*</em>
            </p>

            <h3 class="text-xl sm:text-2xl font-bold mt-8 mb-4">Phase 1: Project Scope & Pricing</h3>
            <p class="mb-6">Please check the box next to each project you would like to include. The prices below are <strong>all-inclusive</strong> for that phase (Materials + Labor).</p>
        </section>

        <div class="space-y-6">
            <!-- PROJECT 1: WALK-IN SHOWER CONVERSION -->
            <div class="p-5 bg-gray-50 rounded-lg shadow-sm">
                <label class="flex items-start">
                    <!-- TOTAL PRICE: $4,655.77 -->
                    <input type="checkbox" data-price="4655.77" class="mt-1 h-6 w-6 text-indigo-600 rounded focus:ring-indigo-500">
                    <span class="ml-4 flex-1 text-base">
                        <span class="text-lg font-semibold text-gray-900 block">1. Tub-to-Walk-in Shower Conversion</span>
                        <p class="text-gray-600 mt-1">
                            <strong>Scope:</strong> Complete removal and disposal of the existing tub and surround. Installation of the new prefabricated shower pan in a mortar bed, three-piece wall system, shower door, and a new shower valve assembly. Includes all necessary plumbing adjustments to relocate the shower valve.
                        </p>
                        <span class="text-xl font-bold text-green-700 mt-2 block">$<span class="price-display">4,655.77</span></span>
                    </span>
                </label>
            </div>
            <!-- END PROJECT BLOCK -->

            <!-- PROJECT 2: COMFORT-HEIGHT TOILET REPLACEMENT -->
            <div class="p-5 bg-gray-50 rounded-lg shadow-sm">
                <label class="flex items-start">
                    <!-- PRICE: $305.58 -->
                    <input type="checkbox" data-price="305.58" class="mt-1 h-6 w-6 text-indigo-600 rounded focus:ring-indigo-500">
                    <span class="ml-4 flex-1 text-base">
                        <span class="text-lg font-semibold text-gray-900 block">2. Comfort-Height Toilet Replacement</span>
                        <p class="text-gray-600 mt-1">
                            <strong>Scope:</strong> Removal and disposal of the existing toilet. Installation and testing of the new comfort-height toilet, including all new installation supplies (wax ring, supply line, bolts).
                        </p>
                        <span class="text-xl font-bold text-green-700 mt-2 block">$<span class="price-display">305.58</span></span>
                    </span>
                </label>
            </div>
            <!-- END PROJECT BLOCK -->
            
            <!-- PROJECT 3: SINK AND FAUCET UPGRADE -->
            <div class="p-5 bg-gray-50 rounded-lg shadow-sm">
                <label class="flex items-start">
                    <!-- PRICE: $621.70 -->
                    <input type="checkbox" data-price="621.70" class="mt-1 h-6 w-6 text-indigo-600 rounded focus:ring-indigo-500">
                    <span class="ml-4 flex-1 text-base">
                        <span class="text-lg font-semibold text-gray-900 block">3. Sink Basin & Faucet Replacement</span>
                        <p class="text-gray-600 mt-1">
                            <strong>Scope:</strong> Removal of the existing sink basin and faucet while retaining the existing countertop. Installation and testing of the new drop-in sink basin, faucet, pop-up drain, P-trap, and new supply lines.
                        </p>
                        <span class="text-xl font-bold text-green-700 mt-2 block">$<span class="price-display">621.70</span></span>
                    </span>
                </label>
            </div>
            <!-- END PROJECT BLOCK -->
            
        </div>
        
        <section class="prose max-w-none text-gray-700 mt-10">
            <h3 class="text-xl sm:text-2xl font-bold mt-8 mb-4">Project Exclusions & Responsibilities</h3>
            <p class="mb-6">The following items are <strong>explicitly not included</strong> in this Guaranteed Maximum Price proposal:</p>
            <ul class="list-disc list-inside space-y-1 text-gray-600">
                <li>Any <strong>electrical work</strong>, including new outlets, lighting, or exhaust fans.</li>
                <li><strong>Painting or final cosmetic finishing</strong> outside the immediate footprint of the new fixtures.</li>
                <li>Any <strong>structural changes</strong> to the home's framing or subfloor beyond what is necessary for a standard installation.</li>
            </ul>
            <h4 class="font-semibold text-base mt-4 text-indigo-700">Client and Contractor Responsibilities:</h4>
            <ul class="list-disc list-inside space-y-1 text-gray-600">
                <li><strong>Permits:</strong> The homeowner is responsible for researching and pulling any required municipal or county permits before work begins.</li>
                <li><strong>Drywall:</strong> Contractor will perform necessary drywall repair/patching behind the shower/tub area, but painting and final cosmetic finishing remains excluded.</li>
            </ul>
            <p class="mt-6 p-3 bg-red-50 text-red-800 rounded-md text-sm border border-red-300">
                <strong>Important Note on Fixed Price:</strong> This proposal is a Fixed Price <strong>Guaranteed Maximum Price (GMP)</strong> contract. The total price is final and comprehensive. The client receives the certainty that the price will not exceed the GMP under any circumstances. The contractor retains any cost savings realized below the GMP.
            </p>
        </section>


        <div class="mt-10 p-6 bg-indigo-50 rounded-lg shadow-md flex justify-between items-center">
            <h4 class="text-xl font-bold text-indigo-800">Total Quote for Selected Projects (GMP):</h4>
            <span id="total-price" class="text-3xl font-extrabold text-indigo-800">$5,583.05</span>
        </div>

        <section class="prose max-w-none text-gray-700 mt-8">
            <h3 class="text-xl sm:text-2xl font-bold mt-8 mb-4">Proposal Acceptance</h3>
            <p class="mb-6">The undersigned agrees to the scope of work and pricing as outlined in this proposal. A signed copy of this document and an initial payment of <strong>50% of the total quote</strong> is required to schedule and begin work.</p>
        </section>

        <div class="mt-8 grid sm:grid-cols-2 gap-8">
            <div>
                <label for="client-name" class="block text-sm font-medium text-gray-700">Client Name</label>
                <input type="text" id="client-name" class="mt-1 block w-full bg-gray-100 px-3 py-2 border border-gray-400 rounded-md focus:outline-none focus:ring-2 focus:ring-indigo-500">
            </div>
            <div>
                <label for="date" class="block text-sm font-medium text-gray-700">Date</label>
                <input type="date" id="date" class="mt-1 block w-full bg-gray-100 px-3 py-2 border border-gray-400 rounded-md focus:outline-none focus:ring-2 focus:ring-indigo-500">
            </div>
        </div>

        <div class="mt-8">
            <label for="signature-pad" class="block text-sm font-medium text-gray-700">Client Signature</label>
            <canvas id="signature-pad" width="400" height="150" class="mt-1"></canvas>
            <div class="mt-2 text-right">
                <button onclick="clearSignature()" class="text-sm text-gray-500 hover:text-gray-700">Clear Signature</button>
            </div>
        </div>

        <div class="mt-10 pt-6 border-t-2 border-dashed border-gray-300">
            <div class="p-4 rounded-lg bg-gray-50 text-gray-700 text-sm">
                <p class="mb-2">To complete and return this proposal:</p>
                <ol class="list-decimal list-inside space-y-1">
                    <li>Fill out the form and check the boxes for the projects you want.</li>
                    <li>Sign the document using the signature pad above.</li>
                    <li>Click the button below to open the print dialog.</li>
                    <li>In the print dialog, select "Save as PDF" as the destination to save a copy.</li>
                    <li>Email the completed PDF to **TheHollandSeven@gmail.com**</li>
                </ol>
            </div>
            
            <div class="mt-6 flex justify-center space-x-4">
                <button onclick="window.print()" class="px-6 py-3 bg-indigo-600 text-white font-semibold rounded-lg shadow-md hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:ring-offset-2">
                    Save as PDF
                </button>
            </div>
        </div>
    </div>

    <script>
        const checkboxes = document.querySelectorAll('input[type="checkbox"]');
        const totalPriceEl = document.getElementById('total-price');

        function updateTotalPrice() {
            let total = 0;
            checkboxes.forEach(checkbox => {
                if (checkbox.checked) {
                    total += parseFloat(checkbox.dataset.price);
                }
            });
            totalPriceEl.textContent = `$${total.toFixed(2)}`;
        }

        checkboxes.forEach(checkbox => {
            checkbox.addEventListener('change', updateTotalPrice);
        });

        // Initial price update on page load
        checkboxes.forEach(checkbox => {
            checkbox.checked = true;
        });
        updateTotalPrice();
        
        // --- Signature Pad Logic ---
        const canvas = document.getElementById('signature-pad');
        const ctx = canvas.getContext('2d');
        let drawing = false;

        function getMousePos(canvas, evt) {
            const rect = canvas.getBoundingClientRect();
            return {
                x: evt.clientX - rect.left,
                y: evt.clientY - rect.top
            };
        }

        function startDrawing(e) {
            drawing = true;
            const pos = getMousePos(canvas, e);
            ctx.beginPath();
            ctx.moveTo(pos.x, pos.y);
            e.preventDefault();
        }

        function draw(e) {
            if (!drawing) return;
            const pos = getMousePos(canvas, e);
            ctx.lineTo(pos.x, pos.y);
            ctx.stroke();
            e.preventDefault();
        }

        function stopDrawing() {
            drawing = false;
        }
        
        // Mouse events
        canvas.addEventListener('mousedown', startDrawing);
        canvas.addEventListener('mouseup', stopDrawing);
        canvas.addEventListener('mousemove', draw);

        // Touch events for mobile
        canvas.addEventListener('touchstart', (e) => startDrawing(e.touches[0]));
        canvas.addEventListener('touchend', stopDrawing);
        canvas.addEventListener('touchmove', (e) => draw(e.touches[0]));
        
        function clearSignature() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);
        }

    </script>
</body>
</html>
