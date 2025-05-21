<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FYJC 2025-26 Round 1 Admission Infographic</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <!-- 
        Chosen Palette: Custom 'Professional Blues & Yellow Accent' 
        - Background: #F0F8FF (Alice Blue, approximated by Tailwind bg-sky-50)
        - Cards: #FFFFFF (White)
        - Primary Text: #1E293B (Dark Slate Gray, Tailwind text-slate-800)
        - Primary Blue: #2563EB (Tailwind blue-600)
        - Lighter Blue: #60A5FA (Tailwind blue-400)
        - Accent Yellow: #FACC15 (Tailwind yellow-400)
        - Warning/Error Color: #EF4444 (Tailwind red-500)
        - Success/Confirmation Color: #22C55E (Tailwind green-500)

        Narrative Plan:
        1. Hero Section: Title, Intro to CAP Round 1.
        2. Online Gateway: Registration (Practice & Actual), Preferences.
        3. Ensuring Fairness: Merit Lists & Grievance Process.
        4. Seat Allocation: Zero Round (Quotas), Round 1 Main Allotment.
        5. Your Allotment: Critical Decisions & Actions (HTML/CSS Flowchart).
        6. Rules of Engagement: Key Instructions (Digital Payment, Timelines).
        7. Student Action & Implication Matrix: Styled HTML Table.
        8. Document Checklist Generator (Client-side, Pre-defined).
        9. Looking Ahead: Next Steps (Round 2 Vacancy).
        10. Footer: Source.

        Visualization Choices Summary (Confirming NO SVG, NO MERMAID JS):
        - Overall Process Timeline (Conceptual Sections): Structured HTML/CSS with Tailwind. Goal: Organize. Justification: Sequence. NO SVG/Mermaid.
        - Registration Windows: Styled Text/Callouts (HTML/Tailwind). Goal: Inform. Justification: Direct. NO SVG.
        - Number of Preferences: Styled Text (HTML/Tailwind). Goal: Inform. Justification: Simple. NO SVG.
        - Merit List & Grievance Process: Structured HTML/CSS steps (HTML/Tailwind). Goal: Organize. Justification: Sub-process. NO SVG/Mermaid.
        - Quota vs. General Seats (Conceptual): Donut Chart (Chart.js - Canvas). Goal: Compare/Inform. Justification: Distinct phases. NO SVG.
        - Info on Allotment Day: Styled List (HTML/Tailwind with Unicode). Goal: Organize. Justification: Itemized. NO SVG.
        - Student Decision Flowchart: Structured HTML/CSS with Tailwind (Flexbox/Grid). Goal: Organize/Inform. Justification: Complex decisions. NO SVG/Mermaid.
        - Key Rules: Icon + Text sections (HTML/Tailwind with Unicode). Goal: Inform. Justification: Highlights. NO SVG.
        - Round 2 Vacancy: Styled Text/Callout (HTML/Tailwind). Goal: Inform. Justification: Direct. NO SVG.
        - Student Action Matrix: Styled HTML Table (Tailwind). Goal: Organize/Compare. Justification: Matrix data. NO SVG.
        - Document Checklist Generator: Pre-defined text list (HTML/Tailwind). Goal: Inform/Assist. Justification: Static content for local use. NO SVG.

        Confirmation: NEITHER Mermaid JS NOR SVG were used anywhere in this output. All visual elements are HTML/CSS/Tailwind or Chart.js (Canvas).
    -->
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #F0F8FF; /* Alice Blue */
        }
        .chart-container {
            position: relative;
            width: 100%;
            margin-left: auto;
            margin-right: auto;
            background-color: white;
            border-radius: 0.5rem; /* rounded-lg */
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06); /* shadow-md */
            padding: 1rem; /* p-4 */
        }
        @media (min-width: 768px) { /* md */
            .chart-container {
                padding: 1.5rem; /* p-6 */
            }
        }
        .flowchart-step {
            border: 2px solid #60A5FA; /* border-blue-400 */
            background-color: white;
            padding: 1rem;
            border-radius: 0.375rem; /* rounded-md */
            text-align: center;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
        }
        .flowchart-connector {
            display: flex;
            align-items: center;
            justify-content: center;
            height: 3rem; /* h-12 */
            width: 100%;
        }
        .flowchart-connector::after {
            content: '';
            display: block;
            width: 2px; /* w-0.5 */
            height: 100%;
            background-color: #9CA3AF; /* bg-gray-400 */
        }
        .flowchart-horizontal-connector {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 2.5rem; /* w-10 */
            height: 100%;
        }
        .flowchart-horizontal-connector::after {
            content: '';
            display: block;
            height: 2px; /* h-0.5 */
            width: 100%;
            background-color: #9CA3AF; /* bg-gray-400 */
        }
        .tooltip-title-multiline { white-space: pre-wrap; }
        .loading-spinner {
            border: 4px solid rgba(0, 0, 0, 0.1);
            border-left-color: #2563EB;
            border-radius: 50%;
            width: 24px;
            height: 24px;
            animation: spin 1s linear infinite;
            display: inline-block;
            vertical-align: middle;
            margin-right: 8px;
        }
        @keyframes spin {
            to { transform: rotate(360deg); }
        }
    </style>
</head>
<body class="text-slate-800">

    <header class="bg-blue-600 text-white py-8 md:py-12">
        <div class="container mx-auto px-4 text-center">
            <h1 class="text-3xl md:text-4xl lg:text-5xl font-bold mb-3">Navigating FYJC Admissions 2025-26</h1>
            <p class="text-lg md:text-xl text-blue-100">A Visual Guide to the Std. 11th Centralized Online Admission Process (CAP): Round 1</p>
        </div>
    </header>

    <main class="container mx-auto px-4 py-8 md:py-12">

        <section id="intro" class="mb-12">
            <div class="bg-white rounded-lg shadow-md p-6 md:p-8">
                <h2 class="text-2xl font-bold text-blue-600 mb-4">Understanding the Process</h2>
                <p class="text-base md:text-lg mb-3">The Directorate of Education (Secondary and Higher Secondary) MS, Pune-1, manages the Std. 11th Centralized Online Admission Process (CAP) for transparent and efficient admissions to Junior Colleges. This guide focuses on 'Round 1', the foundational stage for all applicants.</p>
                <p class="text-base md:text-lg">This infographic breaks down the official Round 1 schedule, offering clear, actionable information to help students and parents navigate the process smoothly and successfully.</p>
            </div>
        </section>

        <section id="registration" class="mb-12">
            <h2 class="text-2xl md:text-3xl font-bold text-blue-600 mb-6 text-center">Phase 1: The Online Gateway - Registration & Preferences</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6 lg:gap-8">
                
                <div class="bg-white rounded-lg shadow-md p-6">
                    <h3 class="text-xl font-semibold text-blue-600 mb-3">Step 1: Practice Makes Perfect</h3>
                    <p class="mb-2"><strong class="text-slate-700">Activity:</strong> Student Registration/Preferences filling (Practice Session)</p>
                    <p class="mb-2"><strong class="text-slate-700">Dates:</strong> <span class="font-medium text-yellow-500">May 19, 2025 (11:00 AM)</span> to <span class="font-medium text-yellow-500">May 20, 2025 (6:00 PM)</span></p>
                    <p class="text-sm text-slate-600 mb-3">This is a crucial opportunity to familiarize yourself with the online portal. All data entered during this practice session will be deleted at midnight on May 20, 2025.</p>
                    <div class="mt-3 p-3 bg-blue-50 rounded-md border border-blue-200">
                        <p class="text-sm font-semibold text-blue-700">Why Practice? To reduce errors during actual application, understand the interface, and build confidence.</p>
                    </div>
                </div>

                <div class="bg-white rounded-lg shadow-md p-6">
                    <h3 class="text-xl font-semibold text-blue-600 mb-3">Step 2: Actual Application Submission</h3>
                    <p class="mb-2"><strong class="text-slate-700">Activity:</strong> Actual Student Registration & Online Application with Preferences</p>
                    <p class="mb-2"><strong class="text-slate-700">Dates:</strong> <span class="font-medium text-yellow-500">May 21, 2025 (11:00 AM)</span> to <span class="font-medium text-yellow-500">May 28, 2025 (6:00 PM)</span></p>
                    <ul class="list-disc list-inside space-y-1 text-slate-700 mb-3">
                        <li>Submit your official application here.</li>
                        <li>Select a minimum of <strong>1</strong> and a maximum of <strong>10</strong> Junior College preferences.</li>
                        <li>Simultaneously apply for Quota admissions (Management/In-house/Minority) if applicable.</li>
                        <li>Consent is required at every round.</li>
                        <li>Non-admitted students can edit preferences/stream after each round.</li>
                    </ul>
                    <div class="mt-3 p-3 bg-yellow-50 rounded-md border border-yellow-300">
                        <p class="text-sm font-semibold text-yellow-700">Strategic Preference Filling: Research colleges and assess your merit. Your choices here are vital for allotment!</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="merit-grievance" class="mb-12">
            <h2 class="text-2xl md:text-3xl font-bold text-blue-600 mb-6 text-center">Phase 2: Ensuring Fairness - Merit Lists & Grievances</h2>
            <div class="bg-white rounded-lg shadow-md p-6 md:p-8">
                <p class="text-center text-slate-600 mb-6">This phase is critical for verifying your ranking and correcting any discrepancies, ensuring the integrity of the admission process.</p>
                <div class="space-y-6">
                    <div class="flex flex-col md:flex-row items-start md:items-center p-4 border border-blue-200 rounded-lg bg-blue-50">
                        <div class="bg-blue-500 text-white rounded-full w-10 h-10 flex items-center justify-center font-bold text-lg mb-3 md:mb-0 md:mr-4">1</div>
                        <div>
                            <h4 class="font-semibold text-blue-700">Display of Provisional General Merit List</h4>
                            <p class="text-slate-700">Date: <span class="font-medium text-yellow-500">May 30, 2025 (11:00 AM)</span></p>
                            <p class="text-sm text-slate-600">Your initial ranking based on submitted data. Review it carefully.</p>
                        </div>
                    </div>
                    <div class="flex flex-col md:flex-row items-start md:items-center p-4 border border-yellow-300 rounded-lg bg-yellow-50">
                        <div class="bg-yellow-400 text-white rounded-full w-10 h-10 flex items-center justify-center font-bold text-lg mb-3 md:mb-0 md:mr-4">2</div>
                        <div>
                            <h4 class="font-semibold text-yellow-700">Objections, Corrections & Online Redressal</h4>
                            <p class="text-slate-700">Window: <span class="font-medium">May 30, 2025 (11:00 AM)</span> to <span class="font-medium">June 1, 2025 (04:00 PM)</span></p>
                            <p class="text-sm text-slate-600">Submit objections/correction requests via "Grievance Redressal" in your student login. The Deputy Director of Education will address these online.</p>
                        </div>
                    </div>
                    <div class="flex flex-col md:flex-row items-start md:items-center p-4 border border-green-300 rounded-lg bg-green-50">
                        <div class="bg-green-500 text-white rounded-full w-10 h-10 flex items-center justify-center font-bold text-lg mb-3 md:mb-0 md:mr-4">3</div>
                        <div>
                            <h4 class="font-semibold text-green-700">Finalization of General Merit List</h4>
                            <p class="text-slate-700">Date: <span class="font-medium text-yellow-500">June 3, 2025 (04:00 PM)</span></p>
                            <p class="text-sm text-slate-600">This is a <strong class="text-red-500">one-time activity</strong>. The list becomes final, forming the basis for allocation.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="allocation" class="mb-12">
            <h2 class="text-2xl md:text-3xl font-bold text-blue-600 mb-6 text-center">Phase 3: The Allotment - Quotas & Round 1</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6 lg:gap-8 items-stretch">
                <div class="bg-white rounded-lg shadow-md p-6 flex flex-col">
                    <h3 class="text-xl font-semibold text-blue-600 mb-3">Zero Round: Quota Admissions</h3>
                    <p class="text-slate-600 mb-3">This round addresses Management, In-House, and Minority Quotas before general merit allocations.</p>
                    <p class="mb-2"><strong class="text-slate-700">Allocation Date:</strong> <span class="font-medium text-yellow-500">June 5, 2025</span></p>
                    <p class="mb-2 text-sm text-slate-600">Allocation audited by divisional CAP committees.</p>
                    <p class="mb-2"><strong class="text-slate-700">Quota Admissions Commence:</strong> <span class="font-medium text-yellow-500">June 6, 2025</span></p>
                    <div class="mt-auto pt-4">
                        <div class="chart-container h-64 md:h-72 max-w-sm">
                            <canvas id="quotaConceptChart"></canvas>
                        </div>
                        <p class="text-xs text-center text-slate-500 mt-2">Conceptual: Quota seats are addressed distinctly.</p>
                    </div>
                </div>

                <div class="bg-white rounded-lg shadow-md p-6">
                    <h3 class="text-xl font-semibold text-blue-600 mb-3">Main Allotment Display for Round 1</h3>
                    <p class="mb-2"><strong class="text-slate-700">Date & Time:</strong> <span class="font-medium text-yellow-500">June 6, 2025 (10:00 AM)</span></p>
                    <p class="text-slate-600 mb-3">The following will be released on the portal:</p>
                    <ul class="list-none space-y-2 text-slate-700">
                        <li class="flex items-start"><span class="text-blue-500 mr-2">➔</span> Jr. College Allotment list for Round 1.</li>
                        <li class="flex items-start"><span class="text-blue-500 mr-2">➔</span> Allotted Jr. College details in student login.</li>
                        <li class="flex items-start"><span class="text-blue-500 mr-2">➔</span> Allotted students list for Jr. Colleges.</li>
                        <li class="flex items-start"><span class="text-blue-500 mr-2">➔</span> Cut-off list for the Admission Round.</li>
                        <li class="flex items-start"><span class="text-blue-500 mr-2">➔</span> SMS notifications to students.</li>
                    </ul>
                    <p class="mt-4 text-sm text-slate-600">Upon viewing, click "Proceed For Admission" if satisfied with the allotted Jr. College.</p>
                    <div class="mt-3 p-3 bg-blue-50 rounded-md border border-blue-200">
                        <p class="text-sm font-semibold text-blue-700">Transparency: Access to allotment and cut-offs empowers informed decisions.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="student-actions" class="mb-12">
            <h2 class="text-2xl md:text-3xl font-bold text-blue-600 mb-6 text-center">Phase 4: Your Allotment - Critical Decisions & Actions</h2>
            <div class="bg-white rounded-lg shadow-md p-6 md:p-8">
                <p class="text-center text-slate-600 mb-2">Action Window: <strong class="text-yellow-500">June 6, 2025 (11:00 AM) to June 12, 2025 (06:00 PM)</strong></p>
                <p class="text-center text-slate-600 mb-6">During this period, you must decide on your allotted college. Understand the rules and consequences carefully.</p>

                <div class="space-y-4">
                    <div class="flowchart-step bg-blue-100 border-blue-500">
                        <p class="font-semibold text-blue-700">You Received an Allotment in Round 1</p>
                    </div>
                    <div class="flowchart-connector"></div>
                    
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-4 items-start">
                        <div class="space-y-2 p-3 border border-red-300 rounded-lg bg-red-50">
                            <div class="flowchart-step">
                                <p class="font-semibold text-slate-700">Was it your <strong class="text-red-600">FIRST PREFERENCE</strong>?</p>
                            </div>
                            <div class="flowchart-connector"></div>
                            <div class="flowchart-step">
                                <p class="font-semibold text-red-600">YES - Admission is COMPULSORY!</p>
                                <p class="text-sm text-slate-600 mt-1">Click 'Proceed for Admission', upload documents, confirm at college.</p>
                            </div>
                            <div class="flowchart-connector"></div>
                            <div class="flowchart-step bg-red-100 border-red-500">
                                <p class="font-semibold text-red-700">CONSEQUENCE of NOT taking admission (or if rejected):</p>
                                <p class="text-sm text-red-600 mt-1">🚫 Blocked for Regular Rounds 2, 3, and 4.</p>
                                <p class="text-sm text-red-600">Eligible only for "open for all" rounds onwards.</p>
                            </div>
                        </div>

                        <div class="space-y-2 p-3 border border-green-300 rounded-lg bg-green-50">
                            <div class="flowchart-step">
                                <p class="font-semibold text-slate-700">Was it your <strong class="text-green-600">FIRST PREFERENCE</strong>?</p>
                            </div>
                            <div class="flowchart-connector"></div>
                            <div class="flowchart-step">
                                <p class="font-semibold text-green-600">NO - You have options:</p>
                            </div>
                            
                            <div class="flex justify-around mt-2">
                                <div class="flowchart-horizontal-connector"></div>
                                <div class="flowchart-horizontal-connector"></div>
                            </div>

                            <div class="grid grid-cols-2 gap-2 items-start">
                                <div class="space-y-1">
                                    <div class="flowchart-step">
                                        <p class="font-semibold text-green-700">Option A: ACCEPT Admission</p>
                                        <p class="text-sm text-slate-600 mt-1">Click 'Proceed for Admission', upload documents, confirm.</p>
                                        <p class="text-xs text-green-600 mt-1">Process complete for this student.</p>
                                    </div>
                                    <div class="flowchart-connector"></div>
                                     <div class="flowchart-step bg-yellow-50 border-yellow-400">
                                        <p class="font-semibold text-yellow-700">If you ACCEPTED & LATER CANCEL:</p>
                                        <p class="text-sm text-yellow-600 mt-1">Request cancellation from Jr. College.</p>
                                        <p class="text-sm text-yellow-600">⚠️ Restricted for consequent Regular Round. Eligible for the round after that.</p>
                                    </div>
                                </div>
                                <div class="space-y-1">
                                   <div class="flowchart-step">
                                        <p class="font-semibold text-blue-700">Option B: WAIT for Next Round</p>
                                        <p class="text-sm text-slate-600 mt-1">Do not click "Proceed for Admission".</p>
                                        <p class="text-xs text-blue-600 mt-1">Eligible for next regular round.</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <p class="text-xs text-center text-slate-500 mt-4">This flowchart simplifies key decision paths. Always refer to official guidelines for full details.</p>
                </div>
                <div class="mt-6 p-4 bg-blue-50 rounded-lg border border-blue-200">
                    <h4 class="text-lg font-semibold text-blue-700 mb-2">Important Notes:</h4>
                    <ul class="list-disc list-inside space-y-1 text-sm text-slate-700">
                        <li>Junior Colleges handle document verification, admission confirmation, rejection, and cancellation via their login.</li>
                        <li>New applicants can register and fill preferences for the NEXT ROUND (with consent).</li>
                    </ul>
                </div>
            </div>
        </section>


        <section id="key-instructions" class="mb-12">
            <h2 class="text-2xl md:text-3xl font-bold text-blue-600 mb-6 text-center">The Rules of Engagement: Key Instructions</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6 lg:gap-8">
                <div class="bg-white rounded-lg shadow-md p-6 text-center">
                    <div class="text-4xl mb-3">💳</div>
                    <h3 class="text-xl font-semibold text-blue-600 mb-2">Digital Fee Payment</h3>
                    <p class="text-slate-600 text-sm">Junior Colleges MUST collect fees ONLY through digital payment modes. No cash transactions.</p>
                    <p class="text-xs text-blue-500 mt-2">Ensures transparency & security.</p>
                </div>
                <div class="bg-white rounded-lg shadow-md p-6 text-center">
                    <div class="text-4xl mb-3">⏰</div>
                    <h3 class="text-xl font-semibold text-blue-600 mb-2">Adherence to Timelines</h3>
                    <p class="text-slate-600 text-sm">All stakeholders (students, colleges, officials) MUST strictly follow the given time limits for all activities.</p>
                    <p class="text-xs text-blue-500 mt-2">Crucial for smooth process flow.</p>
                </div>
                <div class="bg-white rounded-lg shadow-md p-6 text-center">
                    <div class="text-4xl mb-3">✅</div>
                    <h3 class="text-xl font-semibold text-blue-600 mb-2">Status of Confirmed Admissions</h3>
                    <p class="text-slate-600 text-sm">If admission is confirmed (CAP or Quota), the process is complete for that student. They cannot participate in further regular rounds unless they cancel (with consequences).</p>
                    <p class="text-xs text-blue-500 mt-2">Ensures seat management efficiency.</p>
                </div>
            </div>
        </section>
        
        <section id="implication-matrix" class="mb-12">
            <h2 class="text-2xl md:text-3xl font-bold text-blue-600 mb-6 text-center">Student Action & Implication Matrix</h2>
            <div class="bg-white rounded-lg shadow-md p-3 md:p-0 overflow-x-auto">
                <table class="w-full min-w-max text-sm text-left text-slate-700">
                    <thead class="text-xs text-slate-700 uppercase bg-slate-100">
                        <tr>
                            <th scope="col" class="px-4 py-3">Student Action/Scenario</th>
                            <th scope="col" class="px-4 py-3">Implications for Admission Process</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr class="bg-white border-b hover:bg-slate-50">
                            <td class="px-4 py-3 font-medium">Allotted <strong>first preference</strong> & <strong>accepts</strong> admission</td>
                            <td class="px-4 py-3 text-green-600">Admission process is complete.</td>
                        </tr>
                        <tr class="bg-white border-b hover:bg-slate-50">
                            <td class="px-4 py-3 font-medium">Allotted <strong>first preference</strong> & <strong>fails to take admission or rejects</strong> it</td>
                            <td class="px-4 py-3 text-red-600">Blocked for Regular Rounds 2, 3, and 4. Eligible only for "open for all" rounds onwards.</td>
                        </tr>
                        <tr class="bg-white border-b hover:bg-slate-50">
                            <td class="px-4 py-3 font-medium">Allotted <strong>non-first preference</strong> & <strong>accepts</strong> admission</td>
                            <td class="px-4 py-3 text-green-600">Admission process is complete.</td>
                        </tr>
                         <tr class="bg-white border-b hover:bg-slate-50">
                            <td class="px-4 py-3 font-medium">Allotted <strong>non-first preference</strong> & <strong>rejects</strong> it, opting to wait for next round</td>
                            <td class="px-4 py-3 text-blue-600">Eligible for the next regular round.</td>
                        </tr>
                        <tr class="bg-white hover:bg-slate-50">
                            <td class="px-4 py-3 font-medium">Has <strong>confirmed admission</strong> & later <strong>requests cancellation</strong></td>
                            <td class="px-4 py-3 text-yellow-600">Restricted for the consequent Regular Round. Eligible for consideration from the round after that.</td>
                        </tr>
                    </tbody>
                </table>
            </div>
             <p class="text-xs text-center text-slate-500 mt-3">This matrix summarizes key outcomes. Always refer to the official detailed guidelines.</p>
        </section>

        <section id="document-checklist" class="mb-12">
            <h2 class="text-2xl md:text-3xl font-bold text-blue-600 mb-6 text-center">Document Checklist Generator ✨</h2>
            <div class="bg-white rounded-lg shadow-md p-6 md:p-8">
                <p class="text-slate-700 mb-4">Prepare for your admission by generating a personalized document checklist. Select your category below:</p>
                <div class="flex flex-col md:flex-row items-center space-y-4 md:space-y-0 md:space-x-4 mb-6">
                    <label for="categorySelect" class="font-medium text-slate-700">Your Category:</label>
                    <select id="categorySelect" class="flex-grow p-2 border border-blue-300 rounded-md focus:ring-blue-500 focus:border-blue-500">
                        <option value="Open">Open (General)</option>
                        <option value="OBC">OBC (Other Backward Classes)</option>
                        <option value="SC">SC (Scheduled Caste)</option>
                        <option value="ST">ST (Scheduled Tribe)</option>
                        <option value="Minority">Minority (Religious/Linguistic)</option>
                        <option value="EWS">EWS (Economically Weaker Section)</option>
                        <option value="PWD">PWD (Persons with Disability)</option>
                        <option value="Sports">Sports Quota</option>
                        <option value="Defence">Defence Quota</option>
                    </select>
                    <button id="generateChecklistBtn" class="bg-blue-600 text-white px-6 py-2 rounded-md hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-offset-2 transition duration-200 ease-in-out flex items-center justify-center">
                        Generate Checklist ✨
                    </button>
                </div>
                <div id="checklistOutput" class="mt-6 p-4 bg-blue-50 rounded-lg border border-blue-200 min-h-[100px] text-slate-700">
                    <p class="text-center text-slate-500">Your personalized document checklist will appear here.</p>
                </div>
                <p class="text-xs text-slate-500 mt-4 text-center">
                    Disclaimer: This checklist is generated based on common requirements for FYJC admissions in India. Always verify the exact and complete list of required documents with the official admission brochure and your allotted Junior College.
                </p>
            </div>
        </section>

        <section id="next-steps" class="mb-12">
            <h2 class="text-2xl md:text-3xl font-bold text-blue-600 mb-6 text-center">Looking Ahead: What's Next?</h2>
            <div class="bg-white rounded-lg shadow-md p-6 md:p-8 text-center">
                <h3 class="text-xl font-semibold text-blue-600 mb-3">Vacancy Display for Regular Round 2</h3>
                <p class="text-slate-700 text-lg">The official display of vacancies for Regular Round 2 (including any remaining Quota seats) is scheduled for:</p>
                <p class="text-2xl font-bold text-yellow-500 my-4">June 14, 2025 (10:00 PM)</p>
                <p class="text-slate-600">This information is crucial for students not admitted in Round 1 or those waiting for better options. It marks the transition to the next phase of admissions.</p>
            </div>
        </section>

        <section id="conclusion" class="mb-12">
             <div class="bg-blue-50 rounded-lg shadow-md p-6 md:p-8 border border-blue-200">
                <h2 class="text-2xl font-bold text-blue-700 mb-4">Key Takeaways & Advice for Applicants</h2>
                <p class="text-slate-700 mb-3">The Std. 11th CAP Round 1 is designed for fairness and efficiency. Success depends on understanding the process and making informed decisions.</p>
                <ul class="list-disc list-inside space-y-2 text-slate-700 mb-4">
                    <li><strong>Utilize the Practice Session:</strong> Familiarize yourself with the portal.</li>
                    <li><strong>Strategic Preference Filling:</strong> Your first choice is binding if allotted! Research colleges.</li>
                    <li><strong>Meet Deadlines:</strong> Adherence to timelines is critical.</li>
                    <li><strong>Understand Consequences:</strong> Know the implications of rejecting a first preference or cancelling admission.</li>
                    <li><strong>Use Grievance Redressal:</strong> Correct any discrepancies in the provisional merit list.</li>
                    <li><strong>Stay Informed:</strong> Regularly check the official portal and SMS for updates.</li>
                    <li><strong>Prepare Documents:</strong> Have all necessary documents ready for verification.</li>
                </ul>
                <p class="font-semibold text-blue-700">A meticulous approach will significantly enhance your chances of securing admission to your preferred Junior College.</p>
            </div>
        </section>


    </main>

    <footer class="bg-slate-800 text-slate-300 py-8 text-center">
        <div class="container mx-auto px-4">
            <p class="text-sm mb-1">Source: Directorate of Education (Secondary and Higher Secondary) MS, Pune-1.</p>
            <p class="text-xs">This infographic is for informational purposes to simplify the official Std. 11th Centralized Online Admission Process 2025-26, Round 1 Timetable. Always refer to official notifications and websites for definitive information.</p>
            <p class="text-xs mt-2">Infographic by HMN.</p>
        </div>
    </footer>

    <script>
        function wrapLabel(str, maxWidth) {
            if (str.length <= maxWidth) {
                return str;
            }
            const words = str.split(' ');
            const lines = [];
            let currentLine = '';
            for (const word of words) {
                if ((currentLine + word).length <= maxWidth) {
                    currentLine += (currentLine ? ' ' : '') + word;
                } else {
                    if (currentLine) lines.push(currentLine);
                    currentLine = word;
                }
            }
            if (currentLine) lines.push(currentLine);
            return lines.length > 0 ? lines : [str]; // Return array or original string if no split
        }

        const commonTooltipCallback = {
            plugins: {
                tooltip: {
                    callbacks: {
                        title: function(tooltipItems) {
                            const item = tooltipItems[0];
                            let label = item.chart.data.labels[item.dataIndex];
                            if (Array.isArray(label)) {
                              return label.join(' ');
                            } else {
                              return label;
                            }
                        }
                    }
                }
            }
        };

        // Chart for Quota Concept
        const quotaCtx = document.getElementById('quotaConceptChart').getContext('2d');
        if (quotaCtx) {
            new Chart(quotaCtx, {
                type: 'doughnut',
                data: {
                    labels: [wrapLabel('Quota Allocation (Zero Round)', 16), wrapLabel('General Merit Allocation (Round 1)', 16)],
                    datasets: [{
                        label: 'Seat Allocation Phases (Conceptual)',
                        data: [30, 70], // Conceptual data
                        backgroundColor: [
                            '#60A5FA', // Lighter Blue
                            '#2563EB'  // Primary Blue
                        ],
                        borderColor: [
                            '#FFFFFF',
                            '#FFFFFF'
                        ],
                        borderWidth: 2
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    plugins: {
                        legend: {
                            position: 'bottom',
                             labels: {
                                color: '#1E293B', // Primary Text
                                font: { size: 10 }
                            }
                        },
                        title: {
                            display: true,
                            text: 'Conceptual View of Allocation Phases',
                            color: '#1E293B', // Primary Text
                            font: { size: 12, weight: 'bold' }
                        },
                        tooltip: commonTooltipCallback.plugins.tooltip
                    }
                }
            });
        } else {
            console.error("Canvas element for quotaConceptChart not found");
        }

        // Client-Side Document Checklist Data
        const documentChecklists = {
            "Open": [
                "Class 10th Mark Sheet (Original and Attested Copies)",
                "School Leaving Certificate (Original and Attested Copies)",
                "Aadhaar Card (Copy)",
                "Passport Size Photographs (2-3)",
                "Proof of Residence (e.g., Electricity Bill, Ration Card - Copy)",
                "Undertaking/Declaration Form (as per college requirement)"
            ],
            "OBC": [
                "All documents for Open Category",
                "Non-Creamy Layer Certificate (Valid for the current academic year - Original and Attested Copies)",
                "Caste Certificate (Original and Attested Copies)"
            ],
            "SC": [
                "All documents for Open Category",
                "Caste Certificate (Original and Attested Copies)"
            ],
            "ST": [
                "All documents for Open Category",
                "Caste Certificate (Original and Attested Copies)",
                "Caste Validity Certificate (if applicable)"
            ],
            "Minority": [
                "All documents for Open Category",
                "Minority Community Certificate/Affidavit (Original and Attested Copies)",
                "Proof of Minority Status (e.g., self-declaration, school record)"
            ],
            "EWS": [
                "All documents for Open Category",
                "Income and Asset Certificate for EWS (Original and Attested Copies)"
            ],
            "PWD": [
                "All documents for Open Category",
                "Disability Certificate (Issued by competent authority - Original and Attested Copies)"
            ],
            "Sports": [
                "All documents for Open Category",
                "Sports Achievement Certificates (District/State/National level - Original and Attested Copies)",
                "Eligibility Certificate from Sports Authority (if required)"
            ],
            "Defence": [
                "All documents for Open Category",
                "Defence Personnel Certificate (Relevant certificate from competent authority - Original and Attested Copies)",
                "Proof of relationship with defence personnel"
            ]
        };

        const generateChecklistBtn = document.getElementById('generateChecklistBtn');
        const categorySelect = document.getElementById('categorySelect');
        const checklistOutput = document.getElementById('checklistOutput');

        generateChecklistBtn.addEventListener('click', () => {
            const selectedCategory = categorySelect.value;
            const checklist = documentChecklists[selectedCategory];

            if (checklist) {
                const htmlList = checklist.map(item => `<li>${item}</li>`).join('');
                checklistOutput.innerHTML = `<ul class="list-disc list-inside space-y-1">${htmlList}</ul>`;
            } else {
                checklistOutput.innerHTML = '<p class="text-red-500">No checklist found for this category. Please select another or refer to official guidelines.</p>';
            }
        });
    </script>

</body>
</html>
