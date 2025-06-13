<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Overview - Destination Comparison</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }

        .slide {
            background: rgba(255, 255, 255, 0.95);
            color: #333;
            border-radius: 15px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            overflow: hidden;
            max-width: 1200px;
            width: 100%;
            animation: slideIn 0.6s ease-out;
        }

        @keyframes slideIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .slide-header {
            background: linear-gradient(135deg, #ff6b6b, #4ecdc4);
            color: white;
            padding: 30px;
            text-align: center;
        }

        .slide-content {
            padding: 40px;
        }

        h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .comparison-table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        .comparison-table th {
            background: #2c3e50;
            color: white;
            padding: 15px;
            text-align: left;
            font-weight: bold;
        }

        .comparison-table td {
            padding: 15px;
            border-bottom: 1px solid #ddd;
            vertical-align: middle;
        }

        .comparison-table tr:nth-child(even) {
            background: #f8f9fa;
        }

        .comparison-table tr:hover {
            background: #e9ecef;
            transition: background 0.3s ease;
        }

        .destination-name {
            font-weight: bold;
            font-size: 1.1em;
        }

        .cost-range {
            color: #28a745;
            font-weight: bold;
        }

        .visa-status {
            padding: 4px 8px;
            border-radius: 12px;
            font-size: 0.9em;
            font-weight: bold;
        }

        .visa-required {
            background: #ffeaa7;
            color: #d63031;
        }

        .visa-not-required {
            background: #d1f2eb;
            color: #00b894;
        }

        .water-temp {
            font-weight: bold;
            color: #0984e3;
        }

        .highlight-row {
            border-left: 4px solid #ff6b6b;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2em;
            }
            
            .slide-content {
                padding: 20px;
            }

            .comparison-table {
                font-size: 0.9em;
            }

            .comparison-table th,
            .comparison-table td {
                padding: 10px 8px;
            }

            .comparison-table th {
                font-size: 0.8em;
            }
        }

        @media (max-width: 600px) {
            .comparison-table {
                font-size: 0.8em;
            }

            .comparison-table th,
            .comparison-table td {
                padding: 8px 5px;
            }
        }
    </style>
</head>
<body>
    <div class="slide">
        <div class="slide-header">
            <h1>📊 DESTINATION COMPARISON</h1>
            <p style="font-size: 1.1em; margin-top: 10px;">Quick overview of all destination options</p>
        </div>
        <div class="slide-content">
            <table class="comparison-table">
                <thead>
                    <tr>
                        <th>Destination</th>
                        <th>Cost Range</th>
                        <th>Total Travel Time</th>
                        <th>Visa Required</th>
                        <th>Water Temp</th>
                        <th>Best For</th>
                    </tr>
                </thead>
                <tbody>
                    <tr class="highlight-row">
                        <td class="destination-name">🇫🇷🇪🇸 France + Spain (Basque)</td>
                        <td class="cost-range">$1,750-2,580</td>
                        <td>12-14 hours</td>
                        <td><span class="visa-status visa-not-required">❌ No visa needed</span></td>
                        <td class="water-temp">57-61°F</td>
                        <td>Peak surf season, authentic culture</td>
                    </tr>
                    <tr>
                        <td class="destination-name">🇧🇷🇦🇷 Brazil + Argentina</td>
                        <td class="cost-range">$2,200-3,800</td>
                        <td>15-18 hours</td>
                        <td><span class="visa-status visa-required">✅ Brazil e-visa required</span></td>
                        <td class="water-temp">68-77°F</td>
                        <td>Epic culture + world-class nightlife</td>
                    </tr>
                    <tr>
                        <td class="destination-name">🇵🇹🇲🇦 Portugal + Morocco</td>
                        <td class="cost-range">$3,350</td>
                        <td>12-14 hours</td>
                        <td><span class="visa-status visa-not-required">❌ No visa needed</span></td>
                        <td class="water-temp">61-66°F</td>
                        <td>European charm + African adventure</td>
                    </tr>
                    <tr>
                        <td class="destination-name">🇱🇰 Sri Lanka</td>
                        <td class="cost-range">$2,800-3,500</td>
                        <td>22-26 hours</td>
                        <td><span class="visa-status visa-required">✅ eTA required ($50)</span></td>
                        <td class="water-temp">84°F</td>
                        <td>Warm water + cultural immersion</td>
                    </tr>
                    <tr>
                        <td class="destination-name">🇿🇦 South Africa</td>
                        <td class="cost-range">$2,200-3,200</td>
                        <td>20-24 hours</td>
                        <td><span class="visa-status visa-not-required">❌ No visa needed</span></td>
                        <td class="water-temp">60-65°F</td>
                        <td>Adventure + wildlife experiences</td>
                    </tr>
                </tbody>
            </table>

            <div style="background: linear-gradient(135deg, #74b9ff, #0984e3); color: white; padding: 20px; border-radius: 10px; margin-top: 30px; text-align: center;">
                <h3 style="margin-bottom: 10px;">💡 Quick Insights</h3>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 15px; margin-top: 15px;">
                    <div>
                        <strong>🏆 Best Value:</strong><br>
                        Basque Country
                    </div>
                    <div>
                        <strong>🌊 Warmest Water:</strong><br>
                        Sri Lanka (84°F)
                    </div>
                    <div>
                        <strong>✈️ Shortest Travel:</strong><br>
                        Portugal/Basque (12-14hrs)
                    </div>
                    <div>
                        <strong>🎉 Best Nightlife:</strong><br>
                        Brazil + Argentina
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Budget Calculator - Interactive Cost Calculator</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            min-height: 100vh;
            padding: 20px;
        }

        .slide {
            background: rgba(255, 255, 255, 0.95);
            color: #333;
            border-radius: 15px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            overflow: hidden;
            max-width: 1200px;
            width: 100%;
            margin: 0 auto;
            animation: slideIn 0.6s ease-out;
        }

        @keyframes slideIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .slide-header {
            background: linear-gradient(135deg, #ff6b6b, #4ecdc4);
            color: white;
            padding: 30px;
            text-align: center;
        }

        .slide-content {
            padding: 40px;
        }

        h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .budget-calculator {
            background: #f8f9fa;
            padding: 30px;
            border-radius: 15px;
            margin: 20px 0;
            border-left: 5px solid #28a745;
        }

        .calculator-input {
            margin: 20px 0;
            display: flex;
            align-items: center;
            justify-content: space-between;
            flex-wrap: wrap;
            gap: 15px;
        }

        .calculator-input label {
            font-weight: bold;
            min-width: 200px;
            color: #2c3e50;
        }

        .calculator-input input, .calculator-input select {
            flex: 1;
            max-width: 300px;
            padding: 10px 15px;
            border: 2px solid #ddd;
            border-radius: 8px;
            font-size: 16px;
            transition: border-color 0.3s ease;
        }

        .calculator-input input:focus, .calculator-input select:focus {
            outline: none;
            border-color: #3498db;
        }

        .calculator-input input[type="range"] {
            height: 8px;
            background: #ddd;
            border-radius: 5px;
            outline: none;
        }

        .calculator-input input[type="range"]::-webkit-slider-thumb {
            appearance: none;
            width: 20px;
            height: 20px;
            background: #3498db;
            border-radius: 50%;
            cursor: pointer;
        }

        .preference-value {
            font-weight: bold;
            font-size: 1.2em;
            color: #3498db;
            min-width: 40px;
            text-align: center;
        }

        .tabs {
            display: flex;
            border-bottom: 2px solid #ddd;
            margin: 20px 0;
            flex-wrap: wrap;
        }

        .tab {
            background: none;
            border: none;
            padding: 15px 20px;
            cursor: pointer;
            font-size: 14px;
            font-weight: bold;
            border-bottom: 3px solid transparent;
            transition: all 0.3s ease;
            white-space: nowrap;
        }

        .tab.active {
            border-bottom-color: #3498db;
            color: #3498db;
            background: rgba(52, 152, 219, 0.1);
        }

        .tab:hover {
            background: rgba(52, 152, 219, 0.05);
        }

        .tab-content {
            display: none;
            animation: fadeIn 0.3s ease-in;
        }

        .tab-content.active {
            display: block;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .calculator-result {
            background: linear-gradient(135deg, #28a745, #20c997);
            color: white;
            padding: 20px;
            border-radius: 12px;
            text-align: center;
            font-size: 1.3em;
            font-weight: bold;
            margin-top: 20px;
            box-shadow: 0 5px 15px rgba(40, 167, 69, 0.3);
        }

        .cost-breakdown {
            background: white;
            padding: 20px;
            border-radius: 10px;
            margin-top: 15px;
            border: 1px solid #ddd;
        }

        .cost-item {
            display: flex;
            justify-content: space-between;
            padding: 8px 0;
            border-bottom: 1px solid #f1f1f1;
        }

        .cost-item:last-child {
            border-bottom: none;
            font-weight: bold;
            margin-top: 10px;
            padding-top: 15px;
            border-top: 2px solid #28a745;
        }

        .quick-presets {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 15px;
            margin: 20px 0;
        }

        .preset-button {
            background: linear-gradient(135deg, #74b9ff, #0984e3);
            color: white;
            border: none;
            padding: 12px 20px;
            border-radius: 8px;
            cursor: pointer;
            font-weight: bold;
            transition: transform 0.2s ease;
        }

        .preset-button:hover {
            transform: translateY(-2px);
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2em;
            }
            
            .slide-content {
                padding: 20px;
            }

            .calculator-input {
                flex-direction: column;
                align-items: stretch;
            }

            .calculator-input label {
                min-width: auto;
                margin-bottom: 8px;
            }

            .tabs {
                overflow-x: auto;
                white-space: nowrap;
            }

            .tab {
                min-width: 120px;
            }

            .quick-presets {
                grid-template-columns: 1fr 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="slide">
        <div class="slide-header">
            <h1>💰 INTERACTIVE BUDGET CALCULATOR</h1>
            <p style="font-size: 1.1em; margin-top: 10px;">Customize your trip costs based on your preferences</p>
        </div>
        <div class="slide-content">
            <div class="budget-calculator">
                <h3 style="color: #2c3e50; margin-bottom: 20px;">🎛️ Adjust Your Trip Parameters</h3>
                
                <div class="calculator-input">
                    <label>👥 Number of People:</label>
                    <input type="range" id="peopleCount" min="6" max="12" value="8" oninput="updateCalculator()">
                    <span id="peopleDisplay" class="preference-value">8</span>
                </div>
                
                <div class="calculator-input">
                    <label>📅 Trip Duration (Days):</label>
                    <input type="range" id="tripDays" min="10" max="21" value="14" oninput="updateCalculator()">
                    <span id="daysDisplay" class="preference-value">14</span>
                </div>
                
                <div class="calculator-input">
                    <label>🏠 Accommodation Style:</label>
                    <select id="accommodation" onchange="updateCalculator()">
                        <option value="budget">Budget Hostels/Basic Airbnb ($25-40/night)</option>
                        <option value="mid" selected>Mid-range Hotels/Nice Airbnb ($50-80/night)</option>
                        <option value="luxury">Luxury Hotels/Premium Villas ($100-150/night)</option>
                    </select>
                </div>
                
                <div class="calculator-input">
                    <label>🍽️ Food Budget Level:</label>
                    <select id="foodBudget" onchange="updateCalculator()">
                        <option value="budget">Budget Eats ($30-40/day)</option>
                        <option value="mid" selected>Mixed Dining ($50-70/day)</option>
                        <option value="luxury">Fine Dining ($80-120/day)</option>
                    </select>
                </div>
                
                <div class="calculator-input">
                    <label>🎯 Activity Level:</label>
                    <select id="activityLevel" onchange="updateCalculator()">
                        <option value="low">Relaxed ($15-25/day)</option>
                        <option value="medium" selected>Active ($30-50/day)</option>
                        <option value="high">Adventure-packed ($60-100/day)</option>
                    </select>
                </div>

                <h4 style="color: #2c3e50; margin: 25px 0 15px 0;">⚡ Quick Presets</h4>
                <div class="quick-presets">
                    <button class="preset-button" onclick="setPreset('budget')">💸 Budget Trip</button>
                    <button class="preset-button" onclick="setPreset('balanced')">⚖️ Balanced</button>
                    <button class="preset-button" onclick="setPreset('luxury')">✨ Luxury</button>
                </div>
                
                <div class="tabs">
                    <button class="tab active" onclick="showTab('basque-calc')">🇫🇷🇪🇸 Basque</button>
                    <button class="tab" onclick="showTab('brazil-calc')">🇧🇷 Brazil</button>
                    <button class="tab" onclick="showTab('portugal-calc')">🇵🇹 Portugal</button>
                    <button class="tab" onclick="showTab('srilanka-calc')">🇱🇰 Sri Lanka</button>
                    <button class="tab" onclick="showTab('southafrica-calc')">🇿🇦 S.Africa</button>
                </div>

                <div class="tab-content active" id="basque-calc">
                    <div class="calculator-result" id="basqueResult">
                        Total Cost: $2,165 per person | Group Total: $17,320
                    </div>
                    <div class="cost-breakdown" id="basqueBreakdown">
                        <div class="cost-item"><span>✈️ Flights</span><span>$900</span></div>
                        <div class="cost-item"><span>🏠 Accommodation (14 nights)</span><span>$770</span></div>
                        <div class="cost-item"><span>🍽️ Food & Drinks</span><span>$770</span></div>
                        <div class="cost-item"><span>🎯 Activities</span><span>$490</span></div>
                        <div class="cost-item"><span>🚗 Transportation</span><span>$200</span></div>
                        <div class="cost-item"><span>📋 Visas</span><span>$0</span></div>
                        <div class="cost-item"><span><strong>💰 TOTAL PER PERSON</strong></span><span><strong>$3,130</strong></span></div>
                    </div>
                </div>

                <div class="tab-content" id="brazil-calc">
                    <div class="calculator-result" id="brazilResult">
                        Total Cost: $3,000 per person | Group Total: $24,000
                    </div>
                    <div class="cost-breakdown" id="brazilBreakdown">
                        <div class="cost-item"><span>✈️ Flights</span><span>$1,225</span></div>
                        <div class="cost-item"><span>🏠 Accommodation (14 nights)</span><span>$560</span></div>
                        <div class="cost-item"><span>🍽️ Food & Drinks</span><span>$560</span></div>
                        <div class="cost-item"><span>🎯 Activities</span><span>$420</span></div>
                        <div class="cost-item"><span>🚗 Transportation</span><span>$300</span></div>
                        <div class="cost-item"><span>📋 Visas</span><span>$81</span></div>
                        <div class="cost-item"><span><strong>💰 TOTAL PER PERSON</strong></span><span><strong>$3,146</strong></span></div>
                    </div>
                </div>

                <div class="tab-content" id="portugal-calc">
                    <div class="calculator-result" id="portugalResult">
                        Total Cost: $3,350 per person | Group Total: $26,800
                    </div>
                    <div class="cost-breakdown" id="portugalBreakdown">
                        <div class="cost-item"><span>✈️ Flights</span><span>$750</span></div>
                        <div class="cost-item"><span>🏠 Accommodation (14 nights)</span><span>$700</span></div>
                        <div class="cost-item"><span>🍽️ Food & Drinks</span><span>$630</span></div>
                        <div class="cost-item"><span>🎯 Activities</span><span>$448</span></div>
                        <div class="cost-item"><span>🚗 Transportation</span><span>$350</span></div>
                        <div class="cost-item"><span>📋 Visas</span><span>$0</span></div>
                        <div class="cost-item"><span><strong>💰 TOTAL PER PERSON</strong></span><span><strong>$2,878</strong></span></div>
                    </div>
                </div>

                <div class="tab-content" id="srilanka-calc">
                    <div class="calculator-result" id="srilankaResult">
                        Total Cost: $3,150 per person | Group Total: $25,200
                    </div>
                    <div class="cost-breakdown" id="srilankaBreakdown">
                        <div class="cost-item"><span>✈️ Flights</span><span>$1,200</span></div>
                        <div class="cost-item"><span>🏠 Accommodation (14 nights)</span><span>$490</span></div>
                        <div class="cost-item"><span>🍽️ Food & Drinks</span><span>$350</span></div>
                        <div class="cost-item"><span>🎯 Activities</span><span>$350</span></div>
                        <div class="cost-item"><span>🚗 Transportation</span><span>$150</span></div>
                        <div class="cost-item"><span>📋 Visas</span><span>$50</span></div>
                        <div class="cost-item"><span><strong>💰 TOTAL PER PERSON</strong></span><span><strong>$2,590</strong></span></div>
                    </div>
                </div>

                <div class="tab-content" id="southafrica-calc">
                    <div class="calculator-result" id="southafricaResult">
                        Total Cost: $2,700 per person | Group Total: $21,600
                    </div>
                    <div class="cost-breakdown" id="southafricaBreakdown">
                        <div class="cost-item"><span>✈️ Flights</span><span>$1,100</span></div>
                        <div class="cost-item"><span>🏠 Accommodation (14 nights)</span><span>$630</span></div>
                        <div class="cost-item"><span>🍽️ Food & Drinks</span><span>$490</span></div>
                        <div class="cost-item"><span>🎯 Activities</span><span>$392</span></div>
                        <div class="cost-item"><span>🚗 Transportation</span><span>$250</span></div>
                        <div class="cost-item"><span>📋 Visas</span><span>$0</span></div>
                        <div class="cost-item"><span><strong>💰 TOTAL PER PERSON</strong></span><span><strong>$2,862</strong></span></div>
                    </div>
                </div>
            </div>

            <div style="background: linear-gradient(135deg, #74b9ff, #0984e3); color: white; padding: 20px; border-radius: 12px; margin-top: 30px; text-align: center;">
                <h3 style="margin-bottom: 10px;">💡 Money-Saving Tips</h3>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 15px; margin-top: 15px; font-size: 0.9em;">
                    <div>📅 Book flights 2-3 months early</div>
                    <div>🏠 Split large Airbnb rentals</div>
                    <div>🍽️ Mix street food with restaurants</div>
                    <div>🎯 Book activities as a group</div>
                </div>
            </div>
        </div>
    </div>

    <script>
        function updateCalculator() {
            const people = document.getElementById('peopleCount').value;
            const days = document.getElementById('tripDays').value;
            const accommodation = document.getElementById('accommodation').value;
            const food = document.getElementById('foodBudget').value;
            const activities = document.getElementById('activityLevel').value;

            document.getElementById('peopleDisplay').textContent = people;
            document.getElementById('daysDisplay').textContent = days;

            // Base flight costs for each destination
            const flightCosts = {
                basque: 900,
                brazil: 1225,
                portugal: 750,
                srilanka: 1200,
                southafrica: 1100
            };

            // Accommodation rates per night
            const accommodationRates = {
                budget: { basque: 30, brazil: 25, portugal: 35, srilanka: 20, southafrica: 28 },
                mid: { basque: 55, brazil: 40, portugal: 50, srilanka: 35, southafrica: 45 },
                luxury: { basque: 90, brazil: 70, portugal: 85, srilanka: 60, southafrica: 75 }
            };

            // Food rates per day
            const foodRates = {
                budget: { basque: 35, brazil: 25, portugal: 30, srilanka: 15, southafrica: 20 },
                mid: { basque: 55, brazil: 40, portugal: 45, srilanka: 25, southafrica: 35 },
                luxury: { basque: 85, brazil: 70, portugal: 75, srilanka: 45, southafrica: 60 }
            };

            // Activity rates per day
            const activityRates = {
                low: { basque: 20, brazil: 15, portugal: 18, srilanka: 12, southafrica: 15 },
                medium: { basque: 35, brazil: 30, portugal: 32, srilanka: 25, southafrica: 28 },
                high: { basque: 65, brazil: 55, portugal: 60, srilanka: 45, southafrica: 50 }
            };

            // Calculate costs for each destination
            const destinations = ['basque', 'brazil', 'portugal', 'srilanka', 'southafrica'];
            
            destinations.forEach(dest => {
                const flight = flightCosts[dest];
                const accommodationCost = accommodationRates[accommodation][dest] * days;
                const foodCost = foodRates[food][dest] * days;
                const activityCost = activityRates[activities][dest] * days;
                const transport = dest === 'basque' ? 200 : dest === 'brazil' ? 300 : dest === 'portugal' ? 350 : dest === 'srilanka' ? 150 : 250;
                const visa = dest === 'brazil' ? 81 : dest === 'srilanka' ? 50 : 0;
                
                const total = flight + accommodationCost + foodCost + activityCost + transport + visa;
                const groupTotal = total * people;

                document.getElementById(dest + 'Result').innerHTML = 
                    `Total Cost: $${total.toLocaleString()} per person | Group Total: $${groupTotal.toLocaleString()}`;

                // Update breakdown
                const breakdown = document.getElementById(dest + 'Breakdown');
                if (breakdown) {
                    breakdown.innerHTML = `
                        <div class="cost-item"><span>✈️ Flights</span><span>$${flight.toLocaleString()}</span></div>
                        <div class="cost-item"><span>🏠 Accommodation (${days} nights)</span><span>$${accommodationCost.toLocaleString()}</span></div>
                        <div class="cost-item"><span>🍽️ Food & Drinks</span><span>$${foodCost.toLocaleString()}</span></div>
                        <div class="cost-item"><span>🎯 Activities</span><span>$${activityCost.toLocaleString()}</span></div>
                        <div class="cost-item"><span>🚗 Transportation</span><span>$${transport.toLocaleString()}</span></div>
                        <div class="cost-item"><span>📋 Visas</span><span>$${visa}</span></div>
                        <div class="cost-item"><span><strong>💰 TOTAL PER PERSON</strong></span><span><strong>$${total.toLocaleString()}</strong></span></div>
                    `;
                }
            });
        }

        function showTab(tabName) {
            // Hide all tab contents
            const contents = document.querySelectorAll('.tab-content');
            contents.forEach(content => content.classList.remove('active'));

            // Remove active class from all tabs  
            const tabs = document.querySelectorAll('.tab');
            tabs.forEach(tab => tab.classList.remove('active'));

            // Show selected tab content
            document.getElementById(tabName).classList.add('active');
            
            // Add active class to clicked tab
            event.target.classList.add('active');
        }

        function setPreset(preset) {
            if (preset === 'budget') {
                document.getElementById('accommodation').value = 'budget';
                document.getElementById('foodBudget').value = 'budget';
                document.getElementById('activityLevel').value = 'low';
            } else if (preset === 'balanced') {
                document.getElementById('accommodation').value = 'mid';
                document.getElementById('foodBudget').value = 'mid';
                document.getElementById('activityLevel').value = 'medium';
            } else if (preset === 'luxury') {
                document.getElementById('accommodation').value = 'luxury';
                document.getElementById('foodBudget').value = 'luxury';
                document.getElementById('activityLevel').value = 'high';
            }
            updateCalculator();
        }

        // Initialize calculator with default values when page loads
        window.addEventListener('load', function() {
            updateCalculator();
        });
    </script>
</body>
</html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Brazil & Argentina - Spring Season Paradise</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            min-height: 100vh;
            padding: 20px;
        }

        .slide {
            background: rgba(255, 255, 255, 0.95);
            color: #333;
            border-radius: 15px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            overflow: hidden;
            max-width: 1400px;
            width: 100%;
            margin: 0 auto;
            animation: slideIn 0.6s ease-out;
        }

        @keyframes slideIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .slide-header {
            background: linear-gradient(135deg, #00b894, #00cec9);
            color: white;
            padding: 30px;
            text-align: center;
        }

        .slide-content {
            padding: 40px;
        }

        h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        h2 {
            font-size: 2em;
            margin-bottom: 20px;
            color: #2c3e50;
            border-bottom: 3px solid #00b894;
            padding-bottom: 10px;
        }

        h3 {
            font-size: 1.5em;
            margin: 20px 0 10px 0;
            color: #00b894;
        }

        .urgent-notice {
            background: #dc3545;
            color: white;
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
            text-align: center;
            font-weight: bold;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% { opacity: 1; }
            50% { opacity: 0.7; }
            100% { opacity: 1; }
        }

        .destination-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
            gap: 30px;
            margin: 30px 0;
        }

        .destination-card {
            background: white;
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            border-left: 5px solid #00b894;
            transition: transform 0.3s ease;
        }

        .destination-card:hover {
            transform: translateY(-5px);
        }

        .destination-image {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-radius: 10px;
            margin-bottom: 15px;
        }

        .video-container {
            position: relative;
            width: 100%;
            height: 0;
            padding-bottom: 56.25%;
            margin: 20px 0;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }

        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: none;
        }

        .weather-info {
            background: linear-gradient(135deg, #ffecd2, #fcb69f);
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
            color: #333;
        }

        .cost-breakdown {
            background: #f8f9fa;
            border-radius: 10px;
            padding: 20px;
            margin: 20px 0;
            border-left: 5px solid #28a745;
        }

        .cost-item {
            display: flex;
            justify-content: space-between;
            margin: 10px 0;
            padding: 8px 0;
            border-bottom: 1px solid #dee2e6;
        }

        .cost-item:last-child {
            border-bottom: none;
        }

        .total-cost {
            font-weight: bold;
            font-size: 1.2em;
            background: #28a745;
            color: white;
            padding: 15px;
            border-radius: 8px;
            margin-top: 15px;
            text-align: center;
        }

        .pros-cons {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin: 30px 0;
        }

        .pros, .cons {
            padding: 20px;
            border-radius: 10px;
        }

        .pros {
            background: #d4edda;
            border-left: 5px solid #28a745;
        }

        .cons {
            background: #f8d7da;
            border-left: 5px solid #dc3545;
        }

        .pros h3, .cons h3 {
            color: #2c3e50;
            margin-bottom: 15px;
        }

        .pros ul, .cons ul {
            list-style: none;
            padding: 0;
        }

        .pros li, .cons li {
            margin: 8px 0;
            padding-left: 20px;
            position: relative;
        }

        .pros li::before {
            content: "✓";
            position: absolute;
            left: 0;
            color: #28a745;
            font-weight: bold;
        }

        .cons li::before {
            content: "✗";
            position: absolute;
            left: 0;
            color: #dc3545;
            font-weight: bold;
        }

        .link-button {
            display: inline-block;
            background: #007bff;
            color: white;
            padding: 12px 24px;
            text-decoration: none;
            border-radius: 25px;
            margin: 8px;
            transition: all 0.3s ease;
            font-weight: bold;
        }

        .link-button:hover {
            background: #0056b3;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0,123,255,0.3);
        }

        .highlight-section {
            background: linear-gradient(135deg, #00b894, #00cec9);
            color: white;
            padding: 25px;
            border-radius: 15px;
            margin: 30px 0;
            text-align: center;
        }

        .travel-tips {
            background: #e3f2fd;
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
            border-left: 4px solid #2196f3;
        }

        .travel-tips h4 {
            color: #1976d2;
            margin-bottom: 10px;
        }

        .travel-tips ul {
            color: #333;
            padding-left: 20px;
        }

        .travel-tips li {
            margin: 5px 0;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2em;
            }
            
            .slide-content {
                padding: 20px;
            }

            .destination-grid {
                grid-template-columns: 1fr;
                gap: 20px;
            }

            .pros-cons {
                grid-template-columns: 1fr;
            }

            .destination-card {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="slide">
        <div class="slide-header">
            <h1>🇧🇷🇦🇷 BRAZIL & ARGENTINA</h1>
            <p style="font-size: 1.2em; margin-top: 15px;">Spring Season Paradise | November 14-28</p>
            <p style="font-size: 1em; margin-top: 10px;">Rio → Florianópolis → Buenos Aires</p>
        </div>

        <div class="slide-content">
            <div class="urgent-notice">
                🚨 URGENT: Brazil e-visa required as of April 2025 - Apply NOW! ($81 fee + 10-15 business days processing)
            </div>

            <div class="highlight-section">
                <h3 style="color: white; margin-bottom: 15px;">🌟 Why November is Perfect</h3>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; margin-top: 15px;">
                    <div>
                        <strong>🌸 Spring Season</strong><br>
                        Perfect weather, blooming landscapes
                    </div>
                    <div>
                        <strong>🏄‍♂️ Peak Surf</strong><br>
                        Consistent swells in Florianópolis
                    </div>
                    <div>
                        <strong>🎉 Pre-Summer Energy</strong><br>
                        Amazing nightlife before crowds
                    </div>
                    <div>
                        <strong>💰 Better Rates</strong><br>
                        20% cheaper than summer season
                    </div>
                </div>
            </div>
            
            <div class="destination-grid">
                <div class="destination-card">
                    <img src="https://images.unsplash.com/photo-1483729558449-99ef09a8c325?ixlib=rb-4.0.3&auto=format&fit=crop&w=2340&q=80" alt="Rio de Janeiro Christ the Redeemer" class="destination-image">
                    <h3>Rio de Janeiro (5 nights)</h3>
                    <p><strong>The Iconic City:</strong> Christ the Redeemer, Sugarloaf Mountain, Ipanema & Copacabana beaches, legendary Lapa nightlife</p>
                    
                   <iframe width="315" height="315" src="https://www.youtube.com/embed/Ju12Q-yF53g?si=lc3PSufj7mcY08te" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                    
                    <div class="travel-tips">
                        <h4>🎯 Must-Do Experiences</h4>
                        <ul>
                            <li>Sunrise surf session at Barra da Tijuca</li>
                            <li>Cable car to Sugarloaf at sunset</li>
                            <li>Samba night in Lapa district</li>
                            <li>Feijoada lunch in Santa Teresa</li>
                        </ul>
                    </div>
                </div>

                <div class="destination-card">
                    <img src="https://images.unsplash.com/photo-1559827260-dc66d52bef19?ixlib=rb-4.0.3&auto=format&fit=crop&w=2264&q=80" alt="Florianopolis Brazil Beach" class="destination-image">
                    <h3>Florianópolis (4 nights)</h3>
                    <p><strong>Surf Paradise:</strong> Joaquina Beach (world-famous break), consistent November swells, sandboarding, pristine beaches, Brazilian surf culture</p>
                    
                    <iframe width="315" height="315" src="https://www.youtube.com/embed/Bte3SvSZXjU?si=C2ggusM0s1Elw0up" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                    
                    <div class="travel-tips">
                        <h4>🏄‍♂️ Surf Spots Ranking</h4>
                        <ul>
                            <li><strong>Joaquina:</strong> Advanced (6-10ft barrels)</li>
                            <li><strong>Praia Mole:</strong> Intermediate (consistent 3-5ft)</li>
                            <li><strong>Praia Brava:</strong> Beginner-friendly</li>
                            <li><strong>Campeche:</strong> All levels, beautiful setting</li>
                        </ul>
                    </div>
                </div>

                <div class="destination-card">
                    <img src="https://images.unsplash.com/photo-1589649817857-9f5abb4b8f3b?ixlib=rb-4.0.3&auto=format&fit=crop&w=2340&q=80" alt="Buenos Aires Palermo" class="destination-image">
                    <h3>Buenos Aires (4 nights)</h3>
                    <p><strong>Cultural Capital:</strong> World-class tango shows, legendary steaks, Palermo & San Telmo neighborhoods, vibrant spring weather</p>
                    
                    <iframe width="315" height="315" src="https://www.youtube.com/embed/4sbYjI_AtmY?si=D9ulqNLPLvF5Yatb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                    
                    <div class="travel-tips">
                        <h4>🥩 Foodie Paradise</h4>
                        <ul>
                            <li>Parilla dinner at Don Julio (book ahead!)</li>
                            <li>Wine tasting in Palermo Hollywood</li>
                            <li>Empanadas tour in San Telmo</li>
                            <li>Late-night milonga (tango dancing)</li>
                        </ul>
                    </div>
                </div>
            </div>

            <div class="weather-info">
                <h3>🌤️ November Weather Forecast</h3>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 15px; margin-top: 15px;">
                    <div>
                        <strong>Rio de Janeiro:</strong><br>
                        77-86°F (25-30°C)<br>
                        Mostly sunny, occasional afternoon showers
                    </div>
                    <div>
                        <strong>Florianópolis:</strong><br>
                        70-79°F (21-26°C)<br>
                        Perfect surf conditions, light winds
                    </div>
                    <div>
                        <strong>Buenos Aires:</strong><br>
                        68-86°F (20-30°C)<br>
                        Spring blooms, comfortable nights
                    </div>
                </div>
            </div>

            <div class="cost-breakdown">
                <h3>💰 Detailed Cost Breakdown (Per Person)</h3>
                <div class="cost-item">
                    <span><strong>✈️ Flights (Austin → Rio → Floripa → Buenos Aires → Austin)</strong></span>
                    <span><strong>$1,100-1,350</strong></span>
                </div>
                <div class="cost-item">
                    <span>🏠 Accommodations (13 nights total)</span>
                    <span>$200-450</span>
                </div>
                <div class="cost-item">
                    <span>🍽️ Food & Drinks (caipirinha included!)</span>
                    <span>$350-650</span>
                </div>
                <div class="cost-item">
                    <span>🎯 Activities & Tours</span>
                    <span>$250-550</span>
                </div>
                <div class="cost-item">
                    <span>🚗 Local Transportation</span>
                    <span>$200-350</span>
                </div>
                <div class="cost-item">
                    <span>🏄‍♂️ Surf Equipment Rental</span>
                    <span>$80-120</span>
                </div>
                <div class="cost-item">
                    <span>📋 Brazil E-Visa (mandatory)</span>
                    <span>$81</span>
                </div>
                <div class="total-cost">
                    💳 TOTAL RANGE: $2,200-3,800 per person
                </div>
            </div>

            <div class="pros-cons">
                <div class="pros">
                    <h3>✅ Why Brazil + Argentina Rocks</h3>
                    <ul>
                        <li>Perfect spring weather (75-85°F)</li>
                        <li>World-renowned nightlife scenes</li>
                        <li>Excellent surf conditions in Floripa</li>
                        <li>Incredible cultural diversity</li>
                        <li>Amazing food scene (BBQ paradise!)</li>
                        <li>20% cheaper than peak season</li>
                        <li>Epic adventure stories for life</li>
                        <li>Warm, friendly locals</li>
                    </ul>
                </div>
                <div class="cons">
                    <h3>❌ Potential Challenges</h3>
                    <ul>
                        <li>NEW visa requirement for Brazil</li>
                        <li>Long travel time (15+ hours)</li>
                        <li>Higher overall cost</li>
                        <li>Language barrier (Portuguese/Spanish)</li>
                        <li>Complex multi-city logistics</li>
                        <li>Currency exchange considerations</li>
                        <li>Time zone adjustment needed</li>
                        <li>Rainy season transition</li>
                    </ul>
                </div>
            </div>

            <div style="background: #fff3cd; color: #856404; padding: 20px; border-radius: 10px; margin: 20px 0; border-left: 4px solid #ffc107;">
                <h4>⚠️ Important Planning Notes</h4>
                <ul style="margin-top: 10px; padding-left: 20px;">
                    <li><strong>Visa Processing:</strong> Brazil e-visa takes 10-15 business days - apply by January 20th!</li>
                    <li><strong>Flights:</strong> Book multi-city tickets together for better rates</li>
                    <li><strong>Currency:</strong> Brazilian Real (BRL) and Argentine Peso (ARS) - bring USD</li>
                    <li><strong>Health:</strong> No special vaccinations required for these areas</li>
                </ul>
            </div>

            <div style="text-align: center; margin-top: 40px;">
                <h3>🔗 Essential Planning Links</h3>
                <div style="margin-top: 20px;">
                    <a href="https://br.usembassy.gov/message-to-u-s-citizens-new-visitor-visa-requirements-for-u-s-citizens-traveling-to-brazil/" class="link-button" target="_blank">🛂 Brazil Visa Requirements</a>
                    <a href="https://www.airbnb.com/s/Rio-de-Janeiro--Brazil/homes" class="link-button" target="_blank">🏠 Rio Airbnbs</a>
                    <a href="https://www.airbnb.com/s/Florianópolis--Brazil/homes" class="link-button" target="_blank">🏄‍♂️ Floripa Surf Houses</a>
                    <a href="https://www.airbnb.com/s/Buenos-Aires--Argentina/homes" class="link-button" target="_blank">🥩 Buenos Aires Stays</a>
                    <a href="https://www.kayak.com/flights" class="link-button" target="_blank">✈️ Flight Search</a>
                    <a href="https://www.magicseaweed.com/Florianopolis-Surf-Forecast/1103/" class="link-button" target="_blank">🌊 Surf Forecast</a>
                </div>
                
            </div>
        </div>
    </div>
</body>
</html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>France & Spain: Basque Country - Peak Surf Season Paradise</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            min-height: 100vh;
            padding: 20px;
        }

        .slide {
            background: rgba(255, 255, 255, 0.95);
            color: #333;
            border-radius: 15px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            overflow: hidden;
            max-width: 1400px;
            width: 100%;
            margin: 0 auto;
            animation: slideIn 0.6s ease-out;
        }

        @keyframes slideIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .slide-header {
            background: linear-gradient(135deg, #74b9ff, #0984e3);
            color: white;
            padding: 30px;
            text-align: center;
        }

        .slide-content {
            padding: 40px;
        }

        h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        h2 {
            font-size: 2em;
            margin-bottom: 20px;
            color: #2c3e50;
            border-bottom: 3px solid #74b9ff;
            padding-bottom: 10px;
        }

        h3 {
            font-size: 1.5em;
            margin: 20px 0 10px 0;
            color: #74b9ff;
        }

        .destination-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
            gap: 30px;
            margin: 30px 0;
        }

        .destination-card {
            background: white;
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            border-left: 5px solid #74b9ff;
            transition: transform 0.3s ease;
        }

        .destination-card:hover {
            transform: translateY(-5px);
        }

        .destination-image {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-radius: 10px;
            margin-bottom: 15px;
        }

        .video-container {
            position: relative;
            width: 100%;
            height: 0;
            padding-bottom: 56.25%;
            margin: 20px 0;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }

        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: none;
        }

        .weather-info {
            background: linear-gradient(135deg, #ddd6fe, #c7d2fe);
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
            color: #333;
        }

        .cost-breakdown {
            background: #f8f9fa;
            border-radius: 10px;
            padding: 20px;
            margin: 20px 0;
            border-left: 5px solid #28a745;
        }

        .cost-item {
            display: flex;
            justify-content: space-between;
            margin: 10px 0;
            padding: 8px 0;
            border-bottom: 1px solid #dee2e6;
        }

        .cost-item:last-child {
            border-bottom: none;
        }

        .total-cost {
            font-weight: bold;
            font-size: 1.2em;
            background: #28a745;
            color: white;
            padding: 15px;
            border-radius: 8px;
            margin-top: 15px;
            text-align: center;
        }

        .pros-cons {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin: 30px 0;
        }

        .pros, .cons {
            padding: 20px;
            border-radius: 10px;
        }

        .pros {
            background: #d4edda;
            border-left: 5px solid #28a745;
        }

        .cons {
            background: #f8d7da;
            border-left: 5px solid #dc3545;
        }

        .pros h3, .cons h3 {
            color: #2c3e50;
            margin-bottom: 15px;
        }

        .pros ul, .cons ul {
            list-style: none;
            padding: 0;
        }

        .pros li, .cons li {
            margin: 8px 0;
            padding-left: 20px;
            position: relative;
        }

        .pros li::before {
            content: "✓";
            position: absolute;
            left: 0;
            color: #28a745;
            font-weight: bold;
        }

        .cons li::before {
            content: "✗";
            position: absolute;
            left: 0;
            color: #dc3545;
            font-weight: bold;
        }

        .itinerary-day {
            background: #e3f2fd;
            margin: 12px 0;
            padding: 15px;
            border-radius: 8px;
            border-left: 4px solid #2196f3;
            transition: background 0.3s ease;
        }

        .itinerary-day:hover {
            background: #bbdefb;
        }

        .itinerary-day strong {
            color: #1976d2;
        }

        .link-button {
            display: inline-block;
            background: #007bff;
            color: white;
            padding: 12px 24px;
            text-decoration: none;
            border-radius: 25px;
            margin: 8px;
            transition: all 0.3s ease;
            font-weight: bold;
        }

        .link-button:hover {
            background: #0056b3;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0,123,255,0.3);
        }

        .highlight-section {
            background: linear-gradient(135deg, #74b9ff, #0984e3);
            color: white;
            padding: 25px;
            border-radius: 15px;
            margin: 30px 0;
            text-align: center;
        }

        .travel-tips {
            background: #f3e5f5;
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
            border-left: 4px solid #9c27b0;
        }

        .travel-tips h4 {
            color: #7b1fa2;
            margin-bottom: 10px;
        }

        .travel-tips ul {
            color: #333;
            padding-left: 20px;
        }

        .travel-tips li {
            margin: 5px 0;
        }

        .surf-conditions {
            background: linear-gradient(135deg, #00cec9, #55a3ff);
            color: white;
            padding: 20px;
            border-radius: 12px;
            margin: 20px 0;
        }

        .surf-conditions h4 {
            margin-bottom: 15px;
            font-size: 1.2em;
        }

        .surf-spots-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            margin-top: 15px;
        }

        .surf-spot {
            background: rgba(255, 255, 255, 0.2);
            padding: 15px;
            border-radius: 8px;
            text-align: center;
        }

        .pintxos-section {
            background: #fff8e1;
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
            border-left: 4px solid #ff9800;
        }

        .pintxos-section h4 {
            color: #e65100;
            margin-bottom: 10px;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2em;
            }
            
            .slide-content {
                padding: 20px;
            }

            .destination-grid {
                grid-template-columns: 1fr;
                gap: 20px;
            }

            .pros-cons {
                grid-template-columns: 1fr;
            }

            .destination-card {
                padding: 20px;
            }

            .surf-spots-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="slide">
        <div class="slide-header">
            <h1>🇫🇷🇪🇸 FRANCE & SPAIN: BASQUE COUNTRY</h1>
            <p style="font-size: 1.2em; margin-top: 15px;">Peak Surf Season Paradise</p>
            <p style="font-size: 1em; margin-top: 10px;">San Sebastian → Mundaka → Biarritz → Hossegor</p>
        </div>

        <div class="slide-content">
            <div class="highlight-section">
                <h3 style="color: white; margin-bottom: 15px;">🌊 Why November is THE Time for Basque Surf</h3>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; margin-top: 15px;">
                    <div>
                        <strong>🏄‍♂️ Peak Season Begins</strong><br>
                        Consistent Atlantic swells arrive
                    </div>
                    <div>
                        <strong>🌊 3-8ft Waves</strong><br>
                        Perfect size for all skill levels
                    </div>
                    <div>
                        <strong>🏆 World-Class Breaks</strong><br>
                        Mundaka, Hossegor, La Gravière
                    </div>
                    <div>
                        <strong>💰 Off-Season Rates</strong><br>
                        23% cheaper than summer
                    </div>
                </div>
            </div>
            
            <div class="destination-grid">
                <div class="destination-card">
                    <img src="https://images.unsplash.com/photo-1544984243-ec57ea16fe25?ixlib=rb-4.0.3&auto=format&fit=crop&w=2340&q=80" alt="San Sebastian Spain Zurriola Beach" class="destination-image">
                    <h3>San Sebastian, Spain (7 nights)</h3>
                    <p><strong>Pintxos Paradise:</strong> Zurriola Beach city surf, Mundaka day trips, world-renowned Basque cuisine, authentic Spanish culture</p>
                    
                    <div class="video-container">
                      <iframe width="560" height="315" src="https://www.youtube.com/embed/7YbhiVLQoak?si=cJV7sGyed6cQPTeM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                    
                    <div class="pintxos-section">
                        <h4>🍤 Pintxos Bar Crawl Must-Hits</h4>
                        <ul style="color: #333; padding-left: 20px;">
                            <li><strong>La Cuchara de San Telmo:</strong> Gourmet pintxos</li>
                            <li><strong>Gandarias:</strong> Traditional Basque atmosphere</li>
                            <li><strong>Txepetxa:</strong> Famous for anchovies</li>
                            <li><strong>Bar Nestor:</strong> Best tortilla in the city</li>
                        </ul>
                    </div>
                </div>

                <div class="destination-card">
                    <img src="https://images.unsplash.com/photo-1547036967-23d11aacaee0?ixlib=rb-4.0.3&auto=format&fit=crop&w=2340&q=80" alt="Biarritz France Surfing" class="destination-image">
                    <h3>Biarritz, France (7 nights)</h3>
                    <p><strong>Surf Royalty:</strong> Côte des Basques elegance, Hossegor power sessions, refined French coastal culture, surf history birthplace</p>
                    
                    <div class="video-container">
                       <iframe width="560" height="315" src="https://www.youtube.com/embed/agEutF0D2mk?si=AVr274mOqxQk3BLc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                    
                    <div class="travel-tips">
                        <h4>🏛️ Biarritz Cultural Highlights</h4>
                        <ul>
                            <li><strong>Rocher de la Vierge:</strong> Iconic ocean views</li>
                            <li><strong>Aquarium de Biarritz:</strong> Marine life discovery</li>
                            <li><strong>Les Halles:</strong> Traditional French market</li>
                            <li><strong>Casino Barrière:</strong> Evening entertainment</li>
                        </ul>
                    </div>
                </div>
            </div>

            <div class="surf-conditions">
                <h4>🌊 November Surf Conditions - Perfect Timing!</h4>
                <p><strong>Wave Heights:</strong> 3-8ft consistent Atlantic swells | <strong>Water Temp:</strong> 57-61°F | <strong>Wetsuit:</strong> 4/3mm full suit recommended</p>
                
                <div class="surf-spots-grid">
                    <div class="surf-spot">
                        <strong>🏄‍♂️ MUNDAKA</strong><br>
                        World's best left-hand barrel<br>
                        <em>Advanced surfers only</em>
                    </div>
                    <div class="surf-spot">
                        <strong>🌊 HOSSEGOR</strong><br>
                        Powerful beach breaks<br>
                        <em>Intermediate to advanced</em>
                    </div>
                    <div class="surf-spot">
                        <strong>🏖️ ZURRIOLA</strong><br>
                        City beach perfection<br>
                        <em>All skill levels</em>
                    </div>
                    <div class="surf-spot">
                        <strong>🌴 CÔTE DES BASQUES</strong><br>
                        Gentle French elegance<br>
                        <em>Great for beginners</em>
                    </div>
                </div>
            </div>

            <div class="weather-info">
                <h3>🌤️ November Weather Forecast</h3>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 15px; margin-top: 15px;">
                    <div>
                        <strong>San Sebastian:</strong><br>
                        57-64°F (14-18°C)<br>
                        9 hours daylight, occasional rain
                    </div>
                    <div>
                        <strong>Biarritz:</strong><br>
                        59-66°F (15-19°C)<br>
                        Mild Atlantic climate, crisp mornings
                    </div>
                </div>
            </div>

            <h3>📅 14-Day Surf-Focused Itinerary</h3>
            <div class="itinerary-day">
                <strong>Days 1-2:</strong> San Sebastian arrival - Zurriola Beach sessions, pintxos introduction, Old Town exploration
            </div>
            <div class="itinerary-day">
                <strong>Day 3:</strong> Mundaka day trip - World's most famous left-hand barrel (weather permitting)
            </div>
            <div class="itinerary-day">
                <strong>Days 4-6:</strong> San Sebastian deep dive - Local surf spots, Basque culture, food tours, rest day
            </div>
            <div class="itinerary-day">
                <strong>Day 7:</strong> Cross-border travel - San Sebastian to Biarritz (50-minute scenic drive)
            </div>
            <div class="itinerary-day">
                <strong>Days 8-10:</strong> Biarritz exploration - Côte des Basques, Grande Plage, French coastal culture
            </div>
            <div class="itinerary-day">
                <strong>Day 11:</strong> Hossegor power session - Advanced surf breaks, Les Landes forest
            </div>
            <div class="itinerary-day">
                <strong>Days 12-14:</strong> Biarritz finale - Surf lessons, wine tasting, relaxation, departure prep
            </div>

            <div class="cost-breakdown">
                <h3>💰 Cost Breakdown - Best Value Trip! (Per Person)</h3>
                <div class="cost-item">
                    <span><strong>✈️ Flights (Austin → Bilbao, return)</strong></span>
                    <span><strong>$850-950</strong></span>
                </div>
                <div class="cost-item">
                    <span>🏠 Shared villa accommodations (14 nights)</span>
                    <span>$350-500</span>
                </div>
                <div class="cost-item">
                    <span>🍷 Food & pintxos (including wine!)</span>
                    <span>$280-420</span>
                </div>
                <div class="cost-item">
                    <span>🚗 Ground transportation & fuel</span>
                    <span>$200-260</span>
                </div>
                <div class="cost-item">
                    <span>🏄‍♂️ Surf gear rental (wetsuits + boards)</span>
                    <span>$200-250</span>
                </div>
                <div class="cost-item">
                    <span>🎯 Activities & extras</span>
                    <span>$200-400</span>
                </div>
                <div class="total-cost">
                    💳 TOTAL RANGE: $1,750-2,580 per person (BEST VALUE!)
                </div>
            </div>

            <div class="pros-cons">
                <div class="pros">
                    <h3>✅ Why Basque Country Wins</h3>
                    <ul>
                        <li>Peak surf season in November</li>
                        <li>World-class breaks (Mundaka, Hossegor)</li>
                        <li>Incredible food culture (pintxos!)</li>
                        <li>Just 50-minute drive between bases</li>
                        <li>No visa requirements</li>
                        <li>23% lower November accommodation rates</li>
                        <li>Rich Basque culture experience</li>
                        <li>Shortest flight time from Austin</li>
                        <li>Easiest logistics</li>
                        <li>Most budget-friendly option</li>
                    </ul>
                </div>
                <div class="cons">
                    <h3>❌ Potential Challenges</h3>
                    <ul>
                        <li>Cold water (requires 4/3mm wetsuit)</li>
                        <li>Limited daylight hours (9 hours)</li>
                        <li>Frequent rain squalls</li>
                        <li>Crowds at famous breaks</li>
                        <li>Language barrier (Basque/Spanish/French)</li>
                        <li>Weather-dependent surf conditions</li>
                        <li>Higher food costs in tourist areas</li>
                        <li>Limited nightlife compared to Brazil</li>
                    </ul>
                </div>
            </div>

            <div style="background: #e8f5e8; color: #2e7d32; padding: 20px; border-radius: 10px; margin: 20px 0; border-left: 4px solid #4caf50;">
                <h4>🏆 Why This is THE Choice for Surf-Focused Groups</h4>
                <ul style="margin-top: 10px; padding-left: 20px;">
                    <li><strong>Timing:</strong> November is literally the START of peak European surf season</li>
                    <li><strong>Skill Development:</strong> Variety of breaks from beginner to world-class advanced</li>
                    <li><strong>Culture:</strong> Authentic Basque experience in both countries</li>
                    <li><strong>Logistics:</strong> Simplest planning with no visa complications</li>
                    <li><strong>Budget:</strong> Most affordable option with highest quality experience</li>
                </ul>
            </div>

            <div style="text-align: center; margin-top: 40px;">
                <h3>🔗 Essential Basque Surf Resources</h3>
                <div style="margin-top: 20px;">
                    <a href="https://www.ultimatefrance.com/surfing/south-west-france/biarritz" class="link-button" target="_blank">🏄‍♂️ Biarritz Surf Guide</a>
                    <a href="https://thesurfatlas.com/surfing-spain/zarautz-surf/" class="link-button" target="_blank">🌊 Zarautz Conditions</a>
                    <a href="https://www.airbnb.com/biarritz-france/stays" class="link-button" target="_blank">🏠 Biarritz Villas</a>
                    <a href="https://www.likibu.com/us/accommodation/basque-country-san-sebastian" class="link-button" target="_blank">🍤 San Sebastian Stays</a>
                    <a href="https://www.surfline.com/surf-report/mundaka/5842041f4e65fad6a7708be3" class="link-button" target="_blank">📊 Live Surf Forecast</a>
                    <a href="https://www.euskoguide.com/places-basque-country/pintxos-bars-san-sebastian/" class="link-button" target="_blank">🍷 Pintxos Bar Guide</a>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portugal & Morocco - European Charm Meets African Adventure</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            min-height: 100vh;
            padding: 20px;
        }

        .slide {
            background: rgba(255, 255, 255, 0.95);
            color: #333;
            border-radius: 15px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            overflow: hidden;
            max-width: 1400px;
            width: 100%;
            margin: 0 auto;
            animation: slideIn 0.6s ease-out;
        }

        @keyframes slideIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .slide-header {
            background: linear-gradient(135deg, #fd79a8, #fdcb6e);
            color: white;
            padding: 30px;
            text-align: center;
        }

        .slide-content {
            padding: 40px;
        }

        h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        h2 {
            font-size: 2em;
            margin-bottom: 20px;
            color: #2c3e50;
            border-bottom: 3px solid #fd79a8;
            padding-bottom: 10px;
        }

        h3 {
            font-size: 1.5em;
            margin: 20px 0 10px 0;
            color: #fd79a8;
        }

        .destination-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
            gap: 30px;
            margin: 30px 0;
        }

        .destination-card {
            background: white;
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            border-left: 5px solid #fd79a8;
            transition: transform 0.3s ease;
        }

        .destination-card:hover {
            transform: translateY(-5px);
        }

        .destination-image {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-radius: 10px;
            margin-bottom: 15px;
        }

        .video-container {
            position: relative;
            width: 100%;
            height: 0;
            padding-bottom: 56.25%;
            margin: 20px 0;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }

        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: none;
        }

        .weather-info {
            background: linear-gradient(135deg, #ffecd2, #fcb69f);
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
            color: #333;
        }

        .cost-breakdown {
            background: #f8f9fa;
            border-radius: 10px;
            padding: 20px;
            margin: 20px 0;
            border-left: 5px solid #28a745;
        }

        .cost-item {
            display: flex;
            justify-content: space-between;
            margin: 10px 0;
            padding: 8px 0;
            border-bottom: 1px solid #dee2e6;
        }

        .cost-item:last-child {
            border-bottom: none;
        }

        .total-cost {
            font-weight: bold;
            font-size: 1.2em;
            background: #28a745;
            color: white;
            padding: 15px;
            border-radius: 8px;
            margin-top: 15px;
            text-align: center;
        }

        .itinerary-day {
            background: #e3f2fd;
            margin: 12px 0;
            padding: 15px;
            border-radius: 8px;
            border-left: 4px solid #2196f3;
            transition: background 0.3s ease;
        }

        .itinerary-day:hover {
            background: #bbdefb;
        }

        .itinerary-day strong {
            color: #1976d2;
        }

        .link-button {
            display: inline-block;
            background: #007bff;
            color: white;
            padding: 12px 24px;
            text-decoration: none;
            border-radius: 25px;
            margin: 8px;
            transition: all 0.3s ease;
            font-weight: bold;
        }

        .link-button:hover {
            background: #0056b3;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0,123,255,0.3);
        }

        .highlight-section {
            background: linear-gradient(135deg, #fd79a8, #fdcb6e);
            color: white;
            padding: 25px;
            border-radius: 15px;
            margin: 30px 0;
            text-align: center;
        }

        .travel-tips {
            background: #e8f5e8;
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
            border-left: 4px solid #4caf50;
        }

        .travel-tips h4 {
            color: #2e7d32;
            margin-bottom: 10px;
        }

        .travel-tips ul {
            color: #333;
            padding-left: 20px;
        }

        .travel-tips li {
            margin: 5px 0;
        }

        .two-country-banner {
            background: linear-gradient(90deg, #ff6b6b 0%, #ff6b6b 50%, #fd79a8 50%, #fd79a8 100%);
            color: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 12px;
            text-align: center;
            font-weight: bold;
        }

        .ferry-info {
            background: #e1f5fe;
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
            border-left: 4px solid #0288d1;
        }

        .ferry-info h4 {
            color: #01579b;
            margin-bottom: 10px;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2em;
            }
            
            .slide-content {
                padding: 20px;
            }

            .destination-grid {
                grid-template-columns: 1fr;
                gap: 20px;
            }

            .destination-card {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="slide">
        <div class="slide-header">
            <h1>🇵🇹🇲🇦 PORTUGAL & MOROCCO</h1>
            <p style="font-size: 1.2em; margin-top: 15px;">European Charm Meets African Adventure</p>
            <p style="font-size: 1em; margin-top: 10px;">Lisbon → Porto → Ericeira → Tangier → Atlas → Marrakech → Essaouira</p>
        </div>

        <div class="slide-content">
            <div class="two-country-banner">
                🌍 EPIC TWO-CONTINENT ADVENTURE 🌍<br>
                Europe's Atlantic Coast + Africa's Imperial Cities = Unforgettable Journey
            </div>

            <div class="highlight-section">
                <h3 style="color: white; margin-bottom: 15px;">🌟 Why This Combo is Perfect</h3>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; margin-top: 15px;">
                    <div>
                        <strong>🏄‍♂️ World Surfing Reserve</strong><br>
                        Ericeira's consistent November swells
                    </div>
                    <div>
                        <strong>🏛️ Rich History</strong><br>
                        From Roman ruins to imperial palaces
                    </div>
                    <div>
                        <strong>🍷 Amazing Food & Wine</strong><br>
                        Port wine & authentic tagines
                    </div>
                    <div>
                        <strong>✈️ Easy Connection</strong><br>
                        Just 1-hour ferry across Strait
                    </div>
                </div>
            </div>
            
            <div class="destination-grid">
                <div class="destination-card">
                    <img src="https://images.unsplash.com/photo-1544988503-6d5ee3a71b81?ixlib=rb-4.0.3&auto=format&fit=crop&w=2340&q=80" alt="Ericeira Portugal Surf" class="destination-image">
                    <h3>Portugal (7 nights)</h3>
                    <p><strong>Atlantic Surf Paradise:</strong> Lisbon's vibrant culture → Porto's wine cellars → Ericeira World Surfing Reserve with consistent 6-10ft November waves</p>
                    
                    <div class="video-container">
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/zgN_6qPjAgA?si=oE1YnhMgMwrBlRgf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                    
                    <div class="travel-tips">
                        <h4>🏄‍♂️ Ericeira Surf Breaks</h4>
                        <ul>
                            <li><strong>Coxos:</strong> World Championship venue (advanced)</li>
                            <li><strong>Ribeira d'Ilhas:</strong> Perfect right-hand point break</li>
                            <li><strong>Praia de São Sebastião:</strong> Great for beginners</li>
                            <li><strong>Pedra Branca:</strong> Heavy barrel section</li>
                        </ul>
                    </div>
                </div>

                <div class="destination-card">
                    <img src="https://images.unsplash.com/photo-1570204332903-2dd1c3c9bb1b?ixlib=rb-4.0.3&auto=format&fit=crop&w=2340&q=80" alt="Morocco Marrakech Atlas Mountains" class="destination-image">
                    <h3>Morocco (8 nights)</h3>
                    <p><strong>Imperial Kingdom Adventure:</strong> Atlas Mountains trekking → Marrakech's bustling souks → Essaouira's coastal surf town with African flair</p>
                    
                    <div class="video-container">
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/3JY3trh26Uk?si=AbeHrxOLU_dhfQAy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                    
                    <div class="travel-tips">
                        <h4>🏔️ Morocco Highlights</h4>
                        <ul>
                            <li><strong>Atlas Mountains:</strong> Berber village homestays</li>
                            <li><strong>Jemaa el-Fnaa:</strong> UNESCO World Heritage square</li>
                            <li><strong>Bahia Palace:</strong> 19th-century architectural marvel</li>
                            <li><strong>Essaouira:</strong> Windsurfing & coastal surf breaks</li>
                        </ul>
                    </div>
                </div>
            </div>

            <div class="ferry-info">
                <h4>⛴️ Portugal to Morocco Connection</h4>
                <p><strong>Ferry Route:</strong> Quick 1-hour crossing from Tarifa, Spain to Tangier, Morocco</p>
                <ul style="margin-top: 10px; padding-left: 20px;">
                    <li>Multiple daily departures (every 2 hours)</li>
                    <li>Cost: €37-45 per person each way</li>
                    <li>Passport required (no visa for US citizens)</li>
                    <li>Car rental can be arranged on both sides</li>
                </ul>
            </div>

            <div class="weather-info">
                <h3>🌤️ November Weather Conditions</h3>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 15px; margin-top: 15px;">
                    <div>
                        <strong>Portugal:</strong><br>
                        59-68°F (15-20°C)<br>
                        Consistent Atlantic swells<br>
                        <em>Wetsuit: 4/3mm recommended</em>
                    </div>
                    <div>
                        <strong>Morocco:</strong><br>
                        68-77°F (20-25°C)<br>
                        Perfect weather for exploring<br>
                        <em>Wetsuit: 3/2mm for surf</em>
                    </div>
                </div>
            </div>

            <h3>📅 Detailed 15-Day Itinerary</h3>
            <div class="itinerary-day">
                <strong>Days 1-3: Lisbon</strong> - Explore Alfama district, Bairro Alto nightlife, day trip to magical Sintra palaces
            </div>
            <div class="itinerary-day">
                <strong>Days 4-5: Porto</strong> - Port wine tours in Vila Nova de Gaia, Matosinhos Beach surf sessions, historic city center
            </div>
            <div class="itinerary-day">
                <strong>Days 6-7: Ericeira</strong> - World Surfing Reserve, consistent November swells, traditional Portuguese coastal culture
            </div>
            <div class="itinerary-day">
                <strong>Day 8: Travel Day</strong> - Drive to Tarifa, Spain → Ferry to Tangier, Morocco (1 hour crossing + stunning views)
            </div>
            <div class="itinerary-day">
                <strong>Days 9-10: Atlas Mountains</strong> - Berber village trek, traditional tagine cooking, mountain sunrise, authentic cultural exchange
            </div>
            <div class="itinerary-day">
                <strong>Days 11-13: Marrakech</strong> - Jemaa el-Fnaa chaos & charm, souk shopping adventures, traditional riad accommodations
            </div>
            <div class="itinerary-day">
                <strong>Days 14-15: Essaouira</strong> - Coastal surf town, windsurfing capital, fresh seafood, relaxed Atlantic vibes before departure
            </div>

            <div class="cost-breakdown">
                <h3>💰 Total Investment: $3,350 per person</h3>
                <div class="cost-item">
                    <span><strong>✈️ Roundtrip flights to Lisbon</strong></span>
                    <span><strong>$750</strong></span>
                </div>
                <div class="cost-item">
                    <span>🏠 Accommodations (15 nights mix: hotels/riads)</span>
                    <span>$700</span>
                </div>
                <div class="cost-item">
                    <span>🚗 Transportation + Ferry crossing</span>
                    <span>$350</span>
                </div>
                <div class="cost-item">
                    <span>🍽️ Food & Meals (port wine + tagines)</span>
                    <span>$630</span>
                </div>
                <div class="cost-item">
                    <span>🎯 Activities & Tours (Atlas trek, surf lessons)</span>
                    <span>$450</span>
                </div>
                <div class="cost-item">
                    <span>🏄‍♂️ Surf Equipment Rental (Portugal)</span>
                    <span>$250</span>
                </div>
                <div class="cost-item">
                    <span>💡 Miscellaneous & Shopping</span>
                    <span>$220</span>
                </div>
                <div class="total-cost">
                    💳 FIXED PRICE: $3,350 per person (all-inclusive)
                </div>
            </div>

            <div style="background: linear-gradient(135deg, #74b9ff, #0984e3); color: white; padding: 25px; border-radius: 15px; margin: 30px 0;">
                <h3 style="color: white; margin-bottom: 15px;">🌟 Unique Advantages</h3>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; margin-top: 15px;">
                    <div>
                        <strong>🎯 Two Continents</strong><br>
                        Europe + Africa in one trip
                    </div>
                    <div>
                        <strong>🏄‍♂️ World-Class Waves</strong><br>
                        Ericeira's consistent surf
                    </div>
                    <div>
                        <strong>🏛️ Rich Culture</strong><br>
                        From Fado to Gnawa music
                    </div>
                    <div>
                        <strong>📷 Instagram Gold</strong><br>
                        Incredible photo opportunities
                    </div>
                </div>
            </div>

            <div style="background: #fff3cd; color: #856404; padding: 20px; border-radius: 10px; margin: 20px 0; border-left: 4px solid #ffc107;">
                <h4>💡 Pro Travel Tips</h4>
                <ul style="margin-top: 10px; padding-left: 20px;">
                    <li><strong>Currency:</strong> Euro in Portugal, Moroccan Dirham in Morocco</li>
                    <li><strong>Language:</strong> Portuguese & French/Arabic - English widely spoken in tourist areas</li>
                    <li><strong>Packing:</strong> Layer for varying climates, bring wetsuit or rent locally</li>
                    <li><strong>Culture:</strong> Conservative dress in Morocco, especially in Atlas Mountains</li>
                    <li><strong>Bargaining:</strong> Expected in Moroccan souks - start at 30% of asking price</li>
                </ul>
            </div>

            <div style="text-align: center; margin-top: 40px;">
                <h3>🔗 Essential Planning Resources</h3>
                <div style="margin-top: 20px;">
                    <a href="https://www.ericeirasurfhouse.com/" class="link-button" target="_blank">🏄‍♂️ Ericeira Surf Info</a>
                    <a href="https://www.airbnb.com/s/Ericeira--Portugal/homes" class="link-button" target="_blank">🏠 Portugal Surf Rentals</a>
                    <a href="https://www.airbnb.com/s/Marrakech--Morocco/homes" class="link-button" target="_blank">🏛️ Morocco Riads</a>
                    <a href="https://www.frs.es/en" class="link-button" target="_blank">⛴️ Spain-Morocco Ferry</a>
                    <a href="https://www.surfline.com/surf-report/ericeira/5842041f4e65fad6a7708890" class="link-button" target="_blank">🌊 Live Surf Report</a>
                    <a href="https://www.lonelyplanet.com/morocco/atlas-mountains" class="link-button" target="_blank">🏔️ Atlas Mountains Guide</a>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sri Lanka - Tropical Paradise & Cultural Immersion</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            min-height: 100vh;
            padding: 20px;
        }

        .slide {
            background: rgba(255, 255, 255, 0.95);
            color: #333;
            border-radius: 15px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            overflow: hidden;
            max-width: 1400px;
            width: 100%;
            margin: 0 auto;
            animation: slideIn 0.6s ease-out;
        }

        @keyframes slideIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .slide-header {
            background: linear-gradient(135deg, #fdcb6e, #fd79a8);
            color: white;
            padding: 30px;
            text-align: center;
        }

        .slide-content {
            padding: 40px;
        }

        h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        h2 {
            font-size: 2em;
            margin-bottom: 20px;
            color: #2c3e50;
            border-bottom: 3px solid #fdcb6e;
            padding-bottom: 10px;
        }

        h3 {
            font-size: 1.5em;
            margin: 20px 0 10px 0;
            color: #fdcb6e;
        }

        .destination-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
            gap: 30px;
            margin: 30px 0;
        }

        .destination-card {
            background: white;
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            border-left: 5px solid #fdcb6e;
            transition: transform 0.3s ease;
        }

        .destination-card:hover {
            transform: translateY(-5px);
        }

        .destination-image {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-radius: 10px;
            margin-bottom: 15px;
        }

        .video-container {
            position: relative;
            width: 100%;
            height: 0;
            padding-bottom: 56.25%;
            margin: 20px 0;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }

        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: none;
        }

        .weather-info {
            background: linear-gradient(135deg, #74b9ff, #0984e3);
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
            color: white;
        }

        .cost-breakdown {
            background: #f8f9fa;
            border-radius: 10px;
            padding: 20px;
            margin: 20px 0;
            border-left: 5px solid #28a745;
        }

        .cost-item {
            display: flex;
            justify-content: space-between;
            margin: 10px 0;
            padding: 8px 0;
            border-bottom: 1px solid #dee2e6;
        }

        .cost-item:last-child {
            border-bottom: none;
        }

        .total-cost {
            font-weight: bold;
            font-size: 1.2em;
            background: #28a745;
            color: white;
            padding: 15px;
            border-radius: 8px;
            margin-top: 15px;
            text-align: center;
        }

        .pros-cons {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin: 30px 0;
        }

        .pros, .cons {
            padding: 20px;
            border-radius: 10px;
        }

        .pros {
            background: #d4edda;
            border-left: 5px solid #28a745;
        }

        .cons {
            background: #f8d7da;
            border-left: 5px solid #dc3545;
        }

        .pros h3, .cons h3 {
            color: #2c3e50;
            margin-bottom: 15px;
        }

        .pros ul, .cons ul {
            list-style: none;
            padding: 0;
        }

        .pros li, .cons li {
            margin: 8px 0;
            padding-left: 20px;
            position: relative;
        }

        .pros li::before {
            content: "✓";
            position: absolute;
            left: 0;
            color: #28a745;
            font-weight: bold;
        }

        .cons li::before {
            content: "✗";
            position: absolute;
            left: 0;
            color: #dc3545;
            font-weight: bold;
        }

        .link-button {
            display: inline-block;
            background: #007bff;
            color: white;
            padding: 12px 24px;
            text-decoration: none;
            border-radius: 25px;
            margin: 8px;
            transition: all 0.3s ease;
            font-weight: bold;
        }

        .link-button:hover {
            background: #0056b3;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0,123,255,0.3);
        }

        .highlight-section {
            background: linear-gradient(135deg, #fdcb6e, #fd79a8);
            color: white;
            padding: 25px;
            border-radius: 15px;
            margin: 30px 0;
            text-align: center;
        }

        .travel-tips {
            background: #fff8e1;
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
            border-left: 4px solid #ff9800;
        }

        .travel-tips h4 {
            color: #e65100;
            margin-bottom: 10px;
        }

        .travel-tips ul {
            color: #333;
            padding-left: 20px;
        }

        .travel-tips li {
            margin: 5px 0;
        }

        .surf-spots-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            margin-top: 15px;
        }

        .surf-spot {
            background: rgba(255, 255, 255, 0.2);
            padding: 15px;
            border-radius: 8px;
            text-align: center;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2em;
            }
            
            .slide-content {
                padding: 20px;
            }

            .destination-grid {
                grid-template-columns: 1fr;
                gap: 20px;
            }

            .pros-cons {
                grid-template-columns: 1fr;
            }

            .destination-card {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="slide">
        <div class="slide-header">
            <h1>🇱🇰 SRI LANKA</h1>
            <p style="font-size: 1.2em; margin-top: 15px;">Tropical Paradise & Cultural Immersion</p>
            <p style="font-size: 1em; margin-top: 10px;">Colombo → Hikkaduwa → Galle → Arugam Bay → Kandy</p>
        </div>

        <div class="slide-content">
            <div class="highlight-section">
                <h3 style="color: white; margin-bottom: 15px;">🌟 Why Sri Lanka is Perfect for November</h3>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; margin-top: 15px;">
                    <div>
                        <strong>🌊 Warm Water Paradise</strong><br>
                        84°F water - no wetsuit needed!
                    </div>
                    <div>
                        <strong>🏄‍♂️ Perfect Season Switch</strong><br>
                        South coast comes alive in November
                    </div>
                    <div>
                        <strong>🏛️ Rich Culture</strong><br>
                        Ancient temples & colonial history
                    </div>
                    <div>
                        <strong>🐘 Wildlife Adventures</strong><br>
                        Safari parks & elephant encounters
                    </div>
                </div>
            </div>
            
            <div class="destination-grid">
                <div class="destination-card">
                    <img src="https://images.unsplash.com/photo-1566552881560-0be862a7c445?ixlib=rb-4.0.3&auto=format&fit=crop&w=2340&q=80" alt="Arugam Bay Sri Lanka" class="destination-image">
                    <h3>South Coast Surf (8 nights)</h3>
                    <p><strong>Tropical Surf Paradise:</strong> Hikkaduwa's beginner-friendly breaks → Weligama Bay's famous stilt fishermen → Mirissa's stunning beaches and whale watching</p>
                    
                    <div class="video-container">
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/7ZIsD0YH8h4?si=dJ88pJXm7-j7o2qT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                    
                    <div class="travel-tips">
                        <h4>🏄‍♂️ South Coast Surf Spots</h4>
                        <ul>
                            <li><strong>Hikkaduwa:</strong> Perfect for beginners (soft waves)</li>
                            <li><strong>Weligama Bay:</strong> Iconic stilt fishermen backdrop</li>
                            <li><strong>Coconut Tree Hill:</strong> Instagram-famous location</li>
                            <li><strong>Mirissa:</strong> Beach breaks + whale watching</li>
                        </ul>
                    </div>
                </div>

                <div class="destination-card">
                    <img src="https://images.unsplash.com/photo-1544984243-ec57ea16fe25?ixlib=rb-4.0.3&auto=format&fit=crop&w=2340&q=80" alt="Kandy Sri Lanka Temple" class="destination-image">
                    <h3>Cultural Triangle (6 nights)</h3>
                    <p><strong>Ancient Wonders:</strong> Kandy's Temple of the Tooth → Sigiriya Rock Fortress → Polonnaruwa ancient city → Tea plantation tours in the cool mountains</p>
                    
                    <div class="video-container">
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/sCu4bFyvR0Q?si=Ry-yGxcx6wlJbEaM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                    
                    <div class="travel-tips">
                        <h4>🏛️ Cultural Highlights</h4>
                        <ul>
                            <li><strong>Temple of the Tooth:</strong> Sacred Buddhist relic</li>
                            <li><strong>Sigiriya:</strong> Ancient rock fortress (5th century)</li>
                            <li><strong>Tea Plantations:</strong> Cool mountain escape</li>
                            <li><strong>Wildlife Safari:</strong> Elephants at Udawalawe</li>
                        </ul>
                    </div>
                </div>
            </div>

            <div class="weather-info">
                <h3 style="color: white;">🌤️ November Weather - Perfect Timing!</h3>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 15px; margin-top: 15px;">
                    <div>
                        <strong>South Coast:</strong><br>
                        86-90°F (30-32°C)<br>
                        Water: 84°F - tropical paradise!<br>
                        <em>Season: Just starting up</em>
                    </div>
                    <div>
                        <strong>Cultural Triangle:</strong><br>
                        82-88°F (28-31°C)<br>
                        Cool mountain evenings<br>
                        <em>Perfect weather for exploring</em>
                    </div>
                    <div>
                        <strong>Surf Conditions:</strong><br>
                        2-4ft gentle waves<br>
                        No wetsuit needed<br>
                        <em>Ideal for all skill levels</em>
                    </div>
                </div>
            </div>

            <div style="background: linear-gradient(135deg, #00cec9, #55a3ff); color: white; padding: 20px; border-radius: 12px; margin: 20px 0;">
                <h4>🌊 Sri Lanka Surf Season Guide</h4>
                <div class="surf-spots-grid">
                    <div class="surf-spot">
                        <strong>🏄‍♂️ HIKKADUWA</strong><br>
                        Perfect for beginners<br>
                        <em>November-April season</em>
                    </div>
                    <div class="surf-spot">
                        <strong>🌊 WELIGAMA</strong><br>
                        Consistent beach breaks<br>
                        <em>All skill levels</em>
                    </div>
                    <div class="surf-spot">
                        <strong>🏖️ MIRISSA</strong><br>
                        Gentle rollers + whales<br>
                        <em>Beginner paradise</em>
                    </div>
                    <div class="surf-spot">
                        <strong>🌴 COCONUT TREE</strong><br>
                        Instagram famous<br>
                        <em>Perfect photo ops</em>
                    </div>
                </div>
            </div>

            <div class="cost-breakdown">
                <h3>💰 Sri Lanka Cost Breakdown (Per Person)</h3>
                <div class="cost-item">
                    <span><strong>✈️ Flights (Austin → Colombo via Dubai/Qatar)</strong></span>
                    <span><strong>$1,200-1,400</strong></span>
                </div>
                <div class="cost-item">
                    <span>🏠 Accommodations (14 nights, beachfront + cultural)</span>
                    <span>$350-500</span>
                </div>
                <div class="cost-item">
                    <span>🍽️ Food & Drinks (curries + fresh seafood)</span>
                    <span>$280-420</span>
                </div>
                <div class="cost-item">
                    <span>🚗 Private driver + transportation</span>
                    <span>$300-400</span>
                </div>
                <div class="cost-item">
                    <span>🎯 Activities (safari, temples, surf lessons)</span>
                    <span>$250-350</span>
                </div>
                <div class="cost-item">
                    <span>🏄‍♂️ Surf Equipment Rental</span>
                    <span>$100-150</span>
                </div>
                <div class="cost-item">
                    <span>📋 eTA Visa (Electronic Travel Authorization)</span>
                    <span>$50</span>
                </div>
                <div class="total-cost">
                    💳 TOTAL RANGE: $2,530-3,270 per person
                </div>
            </div>

            <div class="pros-cons">
                <div class="pros">
                    <h3>✅ Why Sri Lanka is Incredible</h3>
                    <ul>
                        <li>Warmest water of all options (84°F!)</li>
                        <li>Perfect for beginner/intermediate surfers</li>
                        <li>Incredible cultural experiences</li>
                        <li>Amazing wildlife (elephants, leopards)</li>
                        <li>Delicious, unique cuisine</li>
                        <li>Very affordable once you're there</li>
                        <li>English widely spoken</li>
                        <li>Friendly, welcoming people</li>
                        <li>Stunning natural beauty</li>
                        <li>Great value for money</li>
                    </ul>
                </div>
                <div class="cons">
                    <h3>❌ Potential Challenges</h3>
                    <ul>
                        <li>Longest travel time (22-26 hours total)</li>
                        <li>Jet lag adjustment needed</li>
                        <li>November is transition season (smaller waves)</li>
                        <li>Visa required ($50 eTA)</li>
                        <li>Very hot and humid climate</li>
                        <li>Limited nightlife compared to Brazil</li>
                        <li>Spicy food may not suit everyone</li>
                        <li>Monsoon season unpredictability</li>
                    </ul>
                </div>
            </div>

            <div style="background: #e8f5e8; color: #2e7d32; padding: 20px; border-radius: 10px; margin: 20px 0; border-left: 4px solid #4caf50;">
                <h4>🏆 Why Choose Sri Lanka</h4>
                <ul style="margin-top: 10px; padding-left: 20px;">
                    <li><strong>Unique Experience:</strong> Combine surfing with incredible cultural immersion</li>
                    <li><strong>Beginner Paradise:</strong> Perfect for group members new to surfing</li>
                    <li><strong>Value:</strong> Incredible experiences for your money once you arrive</li>
                    <li><strong>Adventure:</strong> Wildlife safaris, ancient temples, tea plantations</li>
                    <li><strong>Memory Maker:</strong> Completely different from anywhere else you'll visit</li>
                </ul>
            </div>

            <div style="background: #fff3cd; color: #856404; padding: 20px; border-radius: 10px; margin: 20px 0; border-left: 4px solid #ffc107;">
                <h4>⚠️ Important Planning Notes</h4>
                <ul style="margin-top: 10px; padding-left: 20px;">
                    <li><strong>Visa:</strong> eTA required ($50) - apply online 24-48 hours before travel</li>
                    <li><strong>Health:</strong> No special vaccinations required for most travelers</li>
                    <li><strong>Currency:</strong> Sri Lankan Rupee (LKR) - USD widely accepted</li>
                    <li><strong>Surf Season:</strong> November is transition - expect 2-4ft waves, perfect for learning</li>
                    <li><strong>Transport:</strong> Private driver recommended for cultural sites</li>
                </ul>
            </div>

            <div style="text-align: center; margin-top: 40px;">
                <h3>🔗 Essential Sri Lanka Resources</h3>
                <div style="margin-top: 20px;">
                    <a href="https://www.eta.gov.lk/slvisa/" class="link-button" target="_blank">🛂 Sri Lanka eTA Visa</a>
                    <a href="https://www.airbnb.com/s/Hikkaduwa--Sri-Lanka/homes" class="link-button" target="_blank">🏠 Hikkaduwa Accommodations</a>
                    <a href="https://www.perfectwavetravel.com/sri-lanka-surf-guide/" class="link-button" target="_blank">🏄‍♂️ Sri Lanka Surf Guide</a>
                    <a href="https://www.lonelyplanet.com/sri-lanka/the-cultural-triangle" class="link-button" target="_blank">🏛️ Cultural Triangle Guide</a>
                    <a href="https://www.surf-forecast.com/breaks/Hikkaduwa" class="link-button" target="_blank">🌊 Surf Forecast</a>
                    <a href="https://www.srilankatourism.org/" class="link-button" target="_blank">📍 Official Tourism Site</a>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Decision Tool - Weighted Preference System</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            min-height: 100vh;
            padding: 20px;
        }

        .slide {
            background: rgba(255, 255, 255, 0.95);
            color: #333;
            border-radius: 15px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            overflow: hidden;
            max-width: 1200px;
            width: 100%;
            margin: 0 auto;
            animation: slideIn 0.6s ease-out;
        }

        @keyframes slideIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .slide-header {
            background: linear-gradient(135deg, #ff6b6b, #4ecdc4);
            color: white;
            padding: 30px;
            text-align: center;
        }

        .slide-content {
            padding: 40px;
        }

        h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .decision-tool {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            padding: 30px;
            border-radius: 15px;
            margin: 20px 0;
        }

        .instruction-box {
            background: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 30px;
            text-align: center;
        }

        .preference-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin: 30px 0;
        }

        .preference-slider {
            background: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 12px;
            transition: transform 0.2s ease;
        }

        .preference-slider:hover {
            transform: scale(1.02);
        }

        .preference-slider label {
            display: block;
            font-weight: bold;
            margin-bottom: 10px;
            color: white;
            font-size: 1.1em;
        }

        .slider-container {
            display: flex;
            align-items: center;
            gap: 15px;
            margin: 15px 0;
        }

        .preference-slider input[type="range"] {
            flex: 1;
            height: 8px;
            background: rgba(255, 255, 255, 0.3);
            border-radius: 5px;
            outline: none;
            transition: background 0.3s ease;
        }

        .preference-slider input[type="range"]::-webkit-slider-thumb {
            appearance: none;
            width: 24px;
            height: 24px;
            background: #ffd700;
            border-radius: 50%;
            cursor: pointer;
            box-shadow: 0 2px 6px rgba(0,0,0,0.3);
        }

        .preference-value {
            font-weight: bold;
            font-size: 1.4em;
            color: #ffd700;
            min-width: 40px;
            text-align: center;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.3);
        }

        .priority-indicator {
            font-size: 0.9em;
            margin-top: 5px;
            opacity: 0.8;
        }

        .results-section {
            background: white;
            color: #333;
            padding: 30px;
            border-radius: 15px;
            margin-top: 30px;
        }

        .results-header {
            text-align: center;
            margin-bottom: 25px;
            padding-bottom: 15px;
            border-bottom: 2px solid #3498db;
        }

        .destination-scores {
            display: grid;
            gap: 15px;
        }

        .destination-score {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 12px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 15px;
            transition: all 0.3s ease;
            border-left: 5px solid #ddd;
        }

        .destination-score.rank-1 {
            border-left-color: #ffd700;
            background: linear-gradient(135deg, #fff9c4, #f8f9fa);
            transform: scale(1.02);
        }

        .destination-score.rank-2 {
            border-left-color: #c0c0c0;
        }

        .destination-score.rank-3 {
            border-left-color: #cd7f32;
        }

        .destination-name {
            font-weight: bold;
            font-size: 1.1em;
            flex: 1;
            min-width: 200px;
        }

        .score-details {
            display: flex;
            align-items: center;
            gap: 15px;
            flex-wrap: wrap;
        }

        .score-bar {
            width: 200px;
            height: 24px;
            background: #e9ecef;
            border-radius: 12px;
            overflow: hidden;
            position: relative;
        }

        .score-fill {
            height: 100%;
            background: linear-gradient(90deg, #28a745, #20c997);
            transition: width 0.8s ease;
            position: relative;
        }

        .score-fill.top-score {
            background: linear-gradient(90deg, #ffd700, #ffb347);
        }

        .score-percentage {
            font-weight: bold;
            font-size: 1.2em;
            color: #2c3e50;
            min-width: 50px;
        }

        .rank-badge {
            background: #3498db;
            color: white;
            padding: 5px 10px;
            border-radius: 15px;
            font-size: 0.9em;
            font-weight: bold;
        }

        .rank-badge.rank-1 {
            background: #ffd700;
            color: #333;
        }

        .rank-badge.rank-2 {
            background: #c0c0c0;
            color: #333;
        }

        .rank-badge.rank-3 {
            background: #cd7f32;
        }

        .reset-button {
            background: linear-gradient(135deg, #e74c3c, #c0392b);
            color: white;
            border: none;
            padding: 12px 24px;
            border-radius: 8px;
            cursor: pointer;
            font-weight: bold;
            margin: 20px auto;
            display: block;
            transition: transform 0.2s ease;
        }

        .reset-button:hover {
            transform: translateY(-2px);
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2em;
            }
            
            .slide-content {
                padding: 20px;
            }

            .preference-grid {
                grid-template-columns: 1fr;
                gap: 15px;
            }

            .destination-score {
                flex-direction: column;
                text-align: center;
            }

            .score-bar {
                width: 100%;
                max-width: 300px;
            }

            .score-details {
                justify-content: center;
            }
        }
    </style>
</head>
<body>
    <div class="slide">
        <div class="slide-header">
            <h1>🎯 DECISION MAKING TOOL</h1>
            <p style="font-size: 1.1em; margin-top: 10px;">Weight your preferences to find the perfect destination</p>
        </div>
        <div class="slide-content">
            <div class="decision-tool">
                <div class="instruction-box">
                    <h3 style="color: white; margin-bottom: 10px;">📋 How to Use This Tool</h3>
                    <p>Rate each criterion from 1 (not important) to 10 (extremely important). The tool will automatically rank destinations based on your group's priorities!</p>
                </div>

                <h3 style="color: white; border-bottom: 2px solid white; padding-bottom: 10px; margin-bottom: 20px;">
                    ⚖️ Rate Your Priorities (1-10)
                </h3>
                
                <div class="preference-grid">
                    <div class="preference-slider">
                        <label>🏄‍♂️ Surf Quality</label>
                        <div class="slider-container">
                            <span>1</span>
                            <input type="range" id="surfWeight" min="1" max="10" value="8" oninput="updateDecisionTool()">
                            <span>10</span>
                        </div>
                        <div style="text-align: center;">
                            <span id="surfValue" class="preference-value">8</span>
                            <div id="surfIndicator" class="priority-indicator">High Priority</div>
                        </div>
                    </div>

                    <div class="preference-slider">
                        <label>🌡️ Water Temperature</label>
                        <div class="slider-container">
                            <span>1</span>
                            <input type="range" id="tempWeight" min="1" max="10" value="6" oninput="updateDecisionTool()">
                            <span>10</span>
                        </div>
                        <div style="text-align: center;">
                            <span id="tempValue" class="preference-value">6</span>
                            <div id="tempIndicator" class="priority-indicator">Medium Priority</div>
                        </div>
                    </div>

                    <div class="preference-slider">
                        <label>💰 Budget Friendly</label>
                        <div class="slider-container">
                            <span>1</span>
                            <input type="range" id="budgetWeight" min="1" max="10" value="7" oninput="updateDecisionTool()">
                            <span>10</span>
                        </div>
                        <div style="text-align: center;">
                            <span id="budgetValue" class="preference-value">7</span>
                            <div id="budgetIndicator" class="priority-indicator">High Priority</div>
                        </div>
                    </div>

                    <div class="preference-slider">
                        <label>🎉 Nightlife Scene</label>
                        <div class="slider-container">
                            <span>1</span>
                            <input type="range" id="nightlifeWeight" min="1" max="10" value="7" oninput="updateDecisionTool()">
                            <span>10</span>
                        </div>
                        <div style="text-align: center;">
                            <span id="nightlifeValue" class="preference-value">7</span>
                            <div id="nightlifeIndicator" class="priority-indicator">High Priority</div>
                        </div>
                    </div>

                    <div class="preference-slider">
                        <label>🏛️ Cultural Experiences</label>
                        <div class="slider-container">
                            <span>1</span>
                            <input type="range" id="cultureWeight" min="1" max="10" value="8" oninput="updateDecisionTool()">
                            <span>10</span>
                        </div>
                        <div style="text-align: center;">
                            <span id="cultureValue" class="preference-value">8</span>
                            <div id="cultureIndicator" class="priority-indicator">High Priority</div>
                        </div>
                    </div>

                    <div class="preference-slider">
                        <label>🦋 Wildlife & Nature</label>
                        <div class="slider-container">
                            <span>1</span>
                            <input type="range" id="wildlifeWeight" min="1" max="10" value="5" oninput="updateDecisionTool()">
                            <span>10</span>
                        </div>
                        <div style="text-align: center;">
                            <span id="wildlifeValue" class="preference-value">5</span>
                            <div id="wildlifeIndicator" class="priority-indicator">Medium Priority</div>
                        </div>
                    </div>
                </div>

                <button class="reset-button" onclick="resetToDefaults()">🔄 Reset to Defaults</button>
            </div>

            <div class="results-section">
                <div class="results-header">
                    <h3 style="color: #2c3e50;">📊 Destination Rankings</h3>
                    <p style="color: #666; margin-top: 10px;">Based on your weighted preferences</p>
                </div>

                <div class="destination-scores" id="destinationScores">
                    <div class="destination-score rank-1" data-destination="basque">
                        <div class="destination-name">
                            <span class="rank-badge rank-1">#1</span>
                            <strong>🇫🇷🇪🇸 France + Spain (Basque)</strong>
                        </div>
                        <div class="score-details">
                            <div class="score-bar">
                                <div class="score-fill top-score" id="basqueScore" style="width: 85%"></div>
                            </div>
                            <span id="basquePercent" class="score-percentage">85%</span>
                        </div>
                    </div>

                    <div class="destination-score rank-2" data-destination="brazil">
                        <div class="destination-name">
                            <span class="rank-badge rank-2">#2</span>
                            <strong>🇧🇷🇦🇷 Brazil + Argentina</strong>
                        </div>
                        <div class="score-details">
                            <div class="score-bar">
                                <div class="score-fill" id="brazilScore" style="width: 82%"></div>
                            </div>
                            <span id="brazilPercent" class="score-percentage">82%</span>
                        </div>
                    </div>

                    <div class="destination-score rank-3" data-destination="srilanka">
                        <div class="destination-name">
                            <span class="rank-badge rank-3">#3</span>
                            <strong>🇱🇰 Sri Lanka</strong>
                        </div>
                        <div class="score-details">
                            <div class="score-bar">
                                <div class="score-fill" id="srilankaScore" style="width: 78%"></div>
                            </div>
                            <span id="srilankaPercent" class="score-percentage">78%</span>
                        </div>
                    </div>

                    <div class="destination-score" data-destination="portugal">
                        <div class="destination-name">
                            <span class="rank-badge">#4</span>
                            <strong>🇵🇹🇲🇦 Portugal + Morocco</strong>
                        </div>
                        <div class="score-details">
                            <div class="score-bar">
                                <div class="score-fill" id="portugalScore" style="width: 75%"></div>
                            </div>
                            <span id="portugalPercent" class="score-percentage">75%</span>
                        </div>
                    </div>

                    <div class="destination-score" data-destination="southafrica">
                        <div class="destination-name">
                            <span class="rank-badge">#5</span>
                            <strong>🇿🇦 South Africa</strong>
                        </div>
                        <div class="score-details">
                            <div class="score-bar">
                                <div class="score-fill" id="southafricaScore" style="width: 68%"></div>
                            </div>
                            <span id="southafricaPercent" class="score-percentage">68%</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script>
        function updateDecisionTool() {
            const weights = {
                surf: parseInt(document.getElementById('surfWeight').value),
                temp: parseInt(document.getElementById('tempWeight').value),
                budget: parseInt(document.getElementById('budgetWeight').value),
                nightlife: parseInt(document.getElementById('nightlifeWeight').value),
                culture: parseInt(document.getElementById('cultureWeight').value),
                wildlife: parseInt(document.getElementById('wildlifeWeight').value)
            };

            // Update weight displays and priority indicators
            Object.keys(weights).forEach(key => {
                document.getElementById(key + 'Value').textContent = weights[key];
                const indicator = document.getElementById(key + 'Indicator');
                if (weights[key] <= 3) {
                    indicator.textContent = 'Low Priority';
                    indicator.style.color = '#ff7675';
                } else if (weights[key] <= 6) {
                    indicator.textContent = 'Medium Priority';
                    indicator.style.color = '#fdcb6e';
                } else {
                    indicator.textContent = 'High Priority';
                    indicator.style.color = '#55a3ff';
                }
            });

            // Destination ratings (out of 5, matching star ratings)
            const destinations = {
                basque: { surf: 5, temp: 2, budget: 5, nightlife: 4, culture: 5, wildlife: 2 },
                brazil: { surf: 4, temp: 4, budget: 3, nightlife: 5, culture: 5, wildlife: 3 },
                portugal: { surf: 4, temp: 3, budget: 3, nightlife: 3, culture: 5, wildlife: 4 },
                srilanka: { surf: 5, temp: 5, budget: 3, nightlife: 2, culture: 5, wildlife: 5 },
                southafrica: { surf: 4, temp: 2, budget: 4, nightlife: 4, culture: 4, wildlife: 5 }
            };

            const names = {
                basque: '🇫🇷🇪🇸 France + Spain (Basque)',
                brazil: '🇧🇷🇦🇷 Brazil + Argentina',
                portugal: '🇵🇹🇲🇦 Portugal + Morocco',
                srilanka: '🇱🇰 Sri Lanka',
                southafrica: '🇿🇦 South Africa'
            };

            // Calculate weighted scores
            const scores = [];
            Object.keys(destinations).forEach(dest => {
                let totalScore = 0;
                let maxScore = 0;
                
                Object.keys(weights).forEach(criterion => {
                    totalScore += destinations[dest][criterion] * weights[criterion];
                    maxScore += 5 * weights[criterion];
                });

                const percentage = Math.round((totalScore / maxScore) * 100);
                scores.push({ dest, percentage, name: names[dest] });
            });

            // Sort scores descending
            scores.sort((a, b) => b.percentage - a.percentage);

            // Update display
            const scoresContainer = document.getElementById('destinationScores');
            scoresContainer.innerHTML = '';

            scores.forEach((item, index) => {
                const rank = index + 1;
                const scoreElement = document.createElement('div');
                scoreElement.className = `destination-score ${rank <= 3 ? 'rank-' + rank : ''}`;
                scoreElement.setAttribute('data-destination', item.dest);

                scoreElement.innerHTML = `
                    <div class="destination-name">
                        <span class="rank-badge ${rank <= 3 ? 'rank-' + rank : ''}">#${rank}</span>
                        <strong>${item.name}</strong>
                    </div>
                    <div class="score-details">
                        <div class="score-bar">
                            <div class="score-fill ${rank === 1 ? 'top-score' : ''}" style="width: ${item.percentage}%"></div>
                        </div>
                        <span class="score-percentage">${item.percentage}%</span>
                    </div>
                `;

                scoresContainer.appendChild(scoreElement);
            });
        }

        function resetToDefaults() {
            document.getElementById('surfWeight').value = 8;
            document.getElementById('tempWeight').value = 6;
            document.getElementById('budgetWeight').value = 7;
            document.getElementById('nightlifeWeight').value = 7;
            document.getElementById('cultureWeight').value = 8;
            document.getElementById('wildlifeWeight').value = 5;
            updateDecisionTool();
        }

        // Initialize with default values when page loads
        window.addEventListener('load', function() {
            updateDecisionTool();
        });
    </script>
</body>
</html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Final Recommendations - Epic Group Surf Trip 2025</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            min-height: 100vh;
            padding: 20px;
        }

        .slide {
            background: rgba(255, 255, 255, 0.95);
            color: #333;
            border-radius: 15px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            overflow: hidden;
            max-width: 1400px;
            width: 100%;
            margin: 0 auto;
            animation: slideIn 0.6s ease-out;
        }

        @keyframes slideIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .slide-header {
            background: linear-gradient(135deg, #ff6b6b, #4ecdc4);
            color: white;
            padding: 40px;
            text-align: center;
        }

        .slide-content {
            padding: 40px;
        }

        h1 {
            font-size: 2.8em;
            margin-bottom: 15px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        h2 {
            font-size: 2em;
            margin-bottom: 20px;
            color: #2c3e50;
            border-bottom: 3px solid #ff6b6b;
            padding-bottom: 10px;
        }

        h3 {
            font-size: 1.5em;
            margin: 20px 0 10px 0;
            color: #ff6b6b;
        }

        .recommendations-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 30px;
            margin: 40px 0;
        }

        .recommendation-card {
            padding: 30px;
            border-radius: 15px;
            color: white;
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .recommendation-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: inherit;
            opacity: 0.9;
            z-index: -1;
        }

        .recommendation-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 50px rgba(0,0,0,0.2);
        }

        .surf-card {
            background: linear-gradient(135deg, #74b9ff, #0984e3);
        }

        .value-card {
            background: linear-gradient(135deg, #ff6b6b, #feca57);
        }

        .diverse-card {
            background: linear-gradient(135deg, #fd79a8, #fdcb6e);
        }

        .adventure-card {
            background: linear-gradient(135deg, #00b894, #00cec9);
        }

        .recommendation-card h2 {
            color: white;
            border-bottom: 2px solid rgba(255,255,255,0.3);
            padding-bottom: 15px;
            margin-bottom: 20px;
            font-size: 1.8em;
        }

        .recommendation-card h3 {
            color: white;
            margin: 15px 0;
            font-size: 1.4em;
        }

        .recommendation-card p {
            font-size: 1.1em;
            line-height: 1.6;
            margin: 10px 0;
        }

        .timeline-section {
            background: linear-gradient(135deg, #a29bfe, #6c5ce7);
            color: white;
            padding: 30px;
            border-radius: 15px;
            margin: 40px 0;
            text-align: center;
        }

        .timeline-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 25px;
            margin: 30px 0;
        }

        .timeline-item {
            background: rgba(255,255,255,0.15);
            padding: 20px;
            border-radius: 12px;
            transition: background 0.3s ease;
        }

        .timeline-item:hover {
            background: rgba(255,255,255,0.25);
        }

        .timeline-item h3 {
            color: #ffeaa7;
            margin-bottom: 10px;
            font-size: 1.2em;
        }

        .timeline-item p {
            font-size: 0.95em;
            line-height: 1.5;
        }

        .logistics-section {
            background: #f8f9fa;
            border-radius: 15px;
            padding: 30px;
            margin: 30px 0;
            border-left: 5px solid #28a745;
        }

        .logistics-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
            margin: 25px 0;
        }

        .logistics-item {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            border-left: 4px solid #007bff;
        }

        .logistics-item h4 {
            color: #007bff;
            margin-bottom: 10px;
            font-size: 1.1em;
        }

        .logistics-item ul {
            color: #333;
            padding-left: 20px;
            line-height: 1.6;
        }

        .logistics-item li {
            margin: 5px 0;
        }

        .call-to-action {
            background: linear-gradient(135deg, #00b894, #55a3ff);
            color: white;
            padding: 40px;
            border-radius: 15px;
            margin: 40px 0;
            text-align: center;
        }

        .call-to-action h2 {
            color: white;
            border-bottom: 2px solid rgba(255,255,255,0.3);
            padding-bottom: 15px;
            margin-bottom: 25px;
            font-size: 2.2em;
        }

        .call-to-action p {
            font-size: 1.2em;
            margin: 20px 0;
            line-height: 1.6;
        }

        .link-button {
            display: inline-block;
            background: rgba(255,255,255,0.2);
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 25px;
            margin: 10px;
            transition: all 0.3s ease;
            font-weight: bold;
            border: 2px solid rgba(255,255,255,0.3);
        }

        .link-button:hover {
            background: rgba(255,255,255,0.3);
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }

        .final-message {
            background: #fff3cd;
            color: #856404;
            padding: 30px;
            border-radius: 15px;
            margin: 30px 0;
            border-left: 5px solid #ffc107;
            text-align: center;
        }

        .final-message h3 {
            color: #856404;
            margin-bottom: 15px;
            font-size: 1.6em;
        }

        .final-message p {
            font-size: 1.1em;
            line-height: 1.7;
            margin: 10px 0;
        }

        .stats-showcase {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
            margin: 30px 0;
            padding: 25px;
            background: linear-gradient(135deg, #ddd6fe, #c7d2fe);
            border-radius: 12px;
        }

        .stat-item {
            text-align: center;
            padding: 15px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }

        .stat-number {
            font-size: 2em;
            font-weight: bold;
            color: #6c5ce7;
            display: block;
        }

        .stat-label {
            font-size: 0.9em;
            color: #666;
            margin-top: 5px;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2.2em;
            }
            
            .slide-content {
                padding: 20px;
            }

            .recommendations-grid {
                grid-template-columns: 1fr;
                gap: 20px;
            }

            .timeline-grid {
                grid-template-columns: 1fr;
            }

            .logistics-grid {
                grid-template-columns: 1fr;
            }

            .stats-showcase {
                grid-template-columns: repeat(2, 1fr);
            }
        }
    </style>
</head>
<body>
    <div class="slide">
        <div class="slide-header">
            <h1>🏆 FINAL RECOMMENDATIONS</h1>
            <p style="font-size: 1.3em; margin-top: 15px;">The ultimate guide to your epic surf adventure</p>
            <p style="font-size: 1em; margin-top: 10px;">Data-driven decisions for maximum stoke</p>
        </div>

        <div class="slide-content">
            <div class="stats-showcase">
                <div class="stat-item">
                    <span class="stat-number">5</span>
                    <div class="stat-label">Destinations Analyzed</div>
                </div>
                <div class="stat-item">
                    <span class="stat-number">7</span>
                    <div class="stat-label">Criteria Compared</div>
                </div>
                <div class="stat-item">
                    <span class="stat-number">8-10</span>
                    <div class="stat-label">Epic Adventurers</div>
                </div>
                <div class="stat-item">
                    <span class="stat-number">14</span>
                    <div class="stat-label">Days of Adventure</div>
                </div>
            </div>

            <div class="recommendations-grid">
                <div class="recommendation-card surf-card">
                    <h2>🏄‍♂️ BEST SURF CONDITIONS</h2>
                    <h3>France + Spain (Basque)</h3>
                    <p>✅ Peak November surf season</p>
                    <p>✅ World-class breaks (Mundaka, Hossegor)</p>
                    <p>✅ Consistent 3-8ft swells</p>
                    <p>✅ Authentic European surf culture</p>
                    <div style="margin-top: 20px; padding-top: 20px; border-top: 1px solid rgba(255,255,255,0.3);">
                        <strong>Perfect for groups prioritizing surf quality</strong>
                    </div>
                </div>

                <div class="recommendation-card value-card">
                    <h2>🥇 BEST OVERALL VALUE</h2>
                    <h3>France + Spain (Basque)</h3>
                    <p>✅ Lowest total cost ($1,750-2,580)</p>
                    <p>✅ No visa complications</p>
                    <p>✅ Shortest flights from Austin</p>
                    <p>✅ 23% lower November rates</p>
                    <div style="margin-top: 20px; padding-top: 20px; border-top: 1px solid rgba(255,255,255,0.3);">
                        <strong>Best bang for your buck</strong>
                    </div>
                </div>

                <div class="recommendation-card diverse-card">
                    <h2>🌍 MOST DIVERSE EXPERIENCE</h2>
                    <h3>Portugal & Morocco</h3>
                    <p>✅ Two continents in one trip</p>
                    <p>✅ Rich cultural experiences</p>
                    <p>✅ Good surf + adventure blend</p>
                    <p>✅ Unique photo opportunities</p>
                    <div style="margin-top: 20px; padding-top: 20px; border-top: 1px solid rgba(255,255,255,0.3);">
                        <strong>For culture and adventure seekers</strong>
                    </div>
                </div>

                <div class="recommendation-card adventure-card">
                    <h2>🦁 BIGGEST ADVENTURE</h2>
                    <h3>Brazil + Argentina</h3>
                    <p>✅ Perfect spring season weather</p>
                    <p>✅ World-class nightlife scenes</p>
                    <p>✅ Completely different culture</p>
                    <p>✅ Incredible food experiences</p>
                    <div style="margin-top: 20px; padding-top: 20px; border-top: 1px solid rgba(255,255,255,0.3);">
                        <strong>Once-in-a-lifetime experience</strong>
                    </div>
                </div>
            </div>

            <div class="timeline-section">
                <h2 style="color: white; border-bottom: 2px solid white; padding-bottom: 15px;">⏰ CRITICAL BOOKING TIMELINE</h2>
                <p style="font-size: 1.1em; margin: 20px 0;">Time is money - follow this schedule for the best rates and availability!</p>
                
                <div class="timeline-grid">
                    <div class="timeline-item">
                        <h3>📅 January 15, 2025</h3>
                        <p>DEADLINE: All group voting forms completed</p>
                    </div>
                    <div class="timeline-item">
                        <h3>🎯 January 20, 2025</h3>
                        <p>Final destination announcement</p>
                    </div>
                    <div class="timeline-item">
                        <h3>✈️ January 21-25, 2025</h3>
                        <p>Book flights as group for best rates</p>
                    </div>
                    <div class="timeline-item">
                        <h3>🏠 February 1-15, 2025</h3>
                        <p>Reserve group accommodations</p>
                    </div>
                    <div class="timeline-item">
                        <h3>📋 March 1-15, 2025</h3>
                        <p>Finalize activities, visas, gear</p>
                    </div>
                    <div class="timeline-item">
                        <h3>🏄‍♂️ November 14, 2025</h3>
                        <p>DEPARTURE DAY - Epic adventure begins!</p>
                    </div>
                </div>
            </div>

            <div class="logistics-section">
                <h3 style="color: #2c3e50; margin-bottom: 25px;">📋 Group Logistics Master Plan</h3>
                <div class="logistics-grid">
                    <div class="logistics-item">
                        <h4>👥 Group Coordination</h4>
                        <ul>
                            <li>Create dedicated WhatsApp group</li>
                            <li>Designate primary trip coordinator</li>
                            <li>Use Splitwise app for expense tracking</li>
                            <li>Weekly planning check-ins</li>
                        </ul>
                    </div>
                    <div class="logistics-item">
                        <h4>📱 Essential Apps & Tools</h4>
                        <ul>
                            <li>Splitwise (expense management)</li>
                            <li>Google Translate (communication)</li>
                            <li>Surfline/Magic Seaweed (forecasts)</li>
                            <li>Airbnb & Booking.com (accommodations)</li>
                        </ul>
                    </div>
                    <div class="logistics-item">
                        <h4>💼 Travel Insurance & Safety</h4>
                        <ul>
                            <li>$50-100 per person for coverage</li>
                            <li>Include surfing/adventure sports</li>
                            <li>Medical + trip cancellation coverage</li>
                            <li>Group emergency contact list</li>
                        </ul>
                    </div>
                    <div class="logistics-item">
                        <h4>🏄‍♂️ Surf Gear Strategy</h4>
                        <ul>
                            <li>Rent boards locally (easier than flying)</li>
                            <li>Bring personal wetsuit or rent</li>
                            <li>Pack surf accessories (wax, leash)</li>
                            <li>Research local surf shops</li>
                        </ul>
                    </div>
                </div>
            </div>

            <div style="background: linear-gradient(135deg, #fd79a8, #fdcb6e); color: white; padding: 30px; border-radius: 15px; margin: 30px 0;">
                <h3 style="color: white; margin-bottom: 20px;">💡 Pro Tips for Group Travel Success</h3>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; margin-top: 20px;">
                    <div>
                        <strong>🤝 Communication:</strong><br>
                        Over-communicate plans and expectations
                    </div>
                    <div>
                        <strong>💰 Budget Buffer:</strong><br>
                        Add 15-20% buffer for unexpected costs
                    </div>
                    <div>
                        <strong>📋 Backup Plans:</strong><br>
                        Have alternatives for weather/surf conditions
                    </div>
                    <div>
                        <strong>🎯 Flexibility:</strong><br>
                        Be open to itinerary adjustments
                    </div>
                </div>
            </div>

            <div class="call-to-action">
                <h2>🤙 Ready to Book Your Epic Adventure?</h2>
                <p>Any destination you choose will be incredible. The key is making a decision and booking early for the best group rates and maximum stoke!</p>
                <p style="font-style: italic; margin-top: 20px;">"The best time to plant a tree was 20 years ago. The second best time is now. The best time to book an epic surf trip is RIGHT NOW!"</p>
                
                <div style="margin: 30px 0;">
                    <a href="https://www.kayak.com/flights" class="link-button" target="_blank">✈️ Search Group Flights</a>
                    <a href="https://www.airbnb.com/" class="link-button" target="_blank">🏠 Find Group Houses</a>
                    <a href="https://www.worldnomads.com/" class="link-button" target="_blank">🛡️ Travel Insurance</a>
                    <a href="https://splitwise.com/" class="link-button" target="_blank">💰 Expense Tracking</a>
                </div>
            </div>

            <div class="final-message">
                <h3>🌊 The Bottom Line</h3>
                <p>After analyzing 5 world-class destinations across 7 key criteria, <strong>every single option will deliver an incredible experience</strong>. The "best" choice depends on your group's priorities:</p>
                <div style="margin: 20px 0; padding: 20px; background: white; border-radius: 10px;">
                    <p style="color: #333;"><strong>🏄‍♂️ Surf-focused group?</strong> → France + Spain (Basque Country)</p>
                    <p style="color: #333;"><strong>💰 Budget-conscious group?</strong> → France + Spain (Basque Country)</p>
                    <p style="color: #333;"><strong>🌍 Adventure-seeking group?</strong> → Portugal + Morocco or Brazil + Argentina</p>
                    <p style="color: #333;"><strong>🌊 Warm water priority?</strong> → Sri Lanka or Brazil</p>
                </div>
                <p><strong>Most importantly:</strong> Stop debating and start booking! The memories you'll create together are worth far more than the difference between destinations. Let's make this happen! 🤙</p>
            </div>

            <div style="text-align: center; margin: 40px 0; padding: 30px; background: linear-gradient(135deg, #667eea, #764ba2); border-radius: 15px; color: white;">
                <h2 style="color: white; margin-bottom: 20px;">🏄‍♂️ Epic Group Surf Trip 2025 🌊</h2>
                <p style="font-size: 1.3em; margin: 15px 0;">November 14-28, 2025</p>
                <p style="font-size: 1.1em; font-style: italic;">8-10 Friends | Endless Waves | Unforgettable Memories</p>
                <div style="margin-top: 25px; padding-top: 25px; border-top: 1px solid rgba(255,255,255,0.3);">
                    <p style="font-size: 1em;">Questions? Contact the trip coordinator</p>
                    <div style="margin-top: 15px;">
                        <a href="mailto:epic.surf.trip.2025@gmail.com" class="link-button">📧 Email</a>
                        <a href="https://wa.me/15551234567" class="link-button">💬 WhatsApp</a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script>
        // Add some interactive elements
        window.addEventListener('load', function() {
            // Animate the stats on load
            const statNumbers = document.querySelectorAll('.stat-number');
            statNumbers.forEach(stat => {
                const finalNumber = stat.textContent;
                let currentNumber = 0;
                const increment = finalNumber.includes('-') ? 1 : Math.ceil(parseInt(finalNumber) / 20);
                
                const timer = setInterval(() => {
                    if (finalNumber.includes('-')) {
                        stat.textContent = finalNumber;
                        clearInterval(timer);
                    } else {
                        currentNumber += increment;
                        if (currentNumber >= parseInt(finalNumber)) {
                            stat.textContent = finalNumber;
                            clearInterval(timer);
                        } else {
                            stat.textContent = currentNumber;
                        }
                    }
                }, 100);
            });
        });
    </script>
</body>
</html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Group Voting & Preferences - Let's Make This Decision Together</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            min-height: 100vh;
            padding: 20px;
        }

        .slide {
            background: rgba(255, 255, 255, 0.95);
            color: #333;
            border-radius: 15px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            overflow: hidden;
            max-width: 1400px;
            width: 100%;
            margin: 0 auto;
            animation: slideIn 0.6s ease-out;
        }

        @keyframes slideIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .slide-header {
            background: linear-gradient(135deg, #6c5ce7, #a29bfe);
            color: white;
            padding: 30px;
            text-align: center;
        }

        .slide-content {
            padding: 40px;
        }

        h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        h2 {
            font-size: 2em;
            margin-bottom: 20px;
            color: #2c3e50;
            border-bottom: 3px solid #6c5ce7;
            padding-bottom: 10px;
        }

        h3 {
            font-size: 1.5em;
            margin: 20px 0 10px 0;
            color: #6c5ce7;
        }

        .form-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(450px, 1fr));
            gap: 30px;
            margin: 30px 0;
        }

        .form-embed {
            background: #f8f9fa;
            padding: 25px;
            border-radius: 15px;
            text-align: center;
            border-left: 5px solid #6c5ce7;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .form-embed:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 40px rgba(0,0,0,0.15);
        }

        .form-embed h3 {
            color: #2c3e50;
            margin-bottom: 15px;
            font-size: 1.3em;
        }

        .form-embed p {
            color: #666;
            margin-bottom: 20px;
            line-height: 1.6;
        }

        .form-embed iframe {
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        .link-button {
            display: inline-block;
            background: #007bff;
            color: white;
            padding: 12px 24px;
            text-decoration: none;
            border-radius: 25px;
            margin: 10px 5px;
            transition: all 0.3s ease;
            font-weight: bold;
        }

        .link-button:hover {
            background: #0056b3;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0,123,255,0.3);
        }

        .urgent-notice {
            background: #28a745;
            color: white;
            padding: 20px;
            border-radius: 10px;
            margin: 30px 0;
            text-align: center;
            font-weight: bold;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% { opacity: 1; }
            50% { opacity: 0.8; }
            100% { opacity: 1; }
        }

        .results-section {
            background: linear-gradient(135deg, #74b9ff, #0984e3);
            color: white;
            padding: 30px;
            border-radius: 15px;
            margin: 30px 0;
            text-align: center;
        }

        .results-section h3 {
            color: white;
            border-bottom: 2px solid white;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }

        .instruction-box {
            background: #e3f2fd;
            padding: 25px;
            border-radius: 15px;
            margin: 30px 0;
            border-left: 5px solid #2196f3;
        }

        .instruction-box h3 {
            color: #1976d2;
            margin-bottom: 15px;
        }

        .instruction-box ul {
            color: #333;
            padding-left: 20px;
            line-height: 1.8;
        }

        .instruction-box li {
            margin: 8px 0;
        }

        .progress-tracker {
            background: white;
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
            border: 2px solid #ddd;
        }

        .progress-item {
            display: flex;
            align-items: center;
            margin: 15px 0;
            padding: 10px;
            border-radius: 8px;
            transition: background 0.3s ease;
        }

        .progress-item:hover {
            background: #f8f9fa;
        }

        .progress-icon {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 15px;
            font-weight: bold;
            color: white;
        }

        .progress-icon.pending {
            background: #ffc107;
        }

        .progress-icon.complete {
            background: #28a745;
        }

        .progress-text {
            flex: 1;
        }

        .progress-text h4 {
            color: #2c3e50;
            margin-bottom: 5px;
        }

        .progress-text p {
            color: #666;
            font-size: 0.9em;
        }

        .voting-deadline {
            background: linear-gradient(135deg, #fd79a8, #fdcb6e);
            color: white;
            padding: 20px;
            border-radius: 12px;
            margin: 20px 0;
            text-align: center;
            font-size: 1.1em;
            font-weight: bold;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2em;
            }
            
            .slide-content {
                padding: 20px;
            }

            .form-grid {
                grid-template-columns: 1fr;
                gap: 20px;
            }

            .form-embed {
                padding: 20px;
            }

            .form-embed iframe {
                height: 350px;
            }
        }
    </style>
</head>
<body>
    <div class="slide">
        <div class="slide-header">
            <h1>🗳️ GROUP VOTING & PREFERENCES</h1>
            <p style="font-size: 1.2em; margin-top: 15px;">Let's make this decision together!</p>
            <p style="font-size: 1em; margin-top: 10px;">Democracy in action - your voice matters</p>
        </div>

        <div class="slide-content">
            <div class="instruction-box">
                <h3>📋 How This Works</h3>
                <ul>
                    <li><strong>Step 1:</strong> Everyone fills out the form below</li>
                    <li><strong>Step 2:</strong> We analyze the results to see group preferences</li>
                    <li><strong>Step 3:</strong> Final destination decision announced once complete</li>
                    <li><strong>Step 4:</strong> Book flights and accommodations immediately after</li>
                </ul>
                <p style="margin-top: 15px; color: #666; font-style: italic;">
                    <strong>Important:</strong> Please be honest about your preferences and budget constraints. This helps us pick the best trip for EVERYONE!
                </p>
            </div>

            <div class="form-grid">
                <div class="form-embed">
                    <h3>🏆 Vote for Your Top 3 Destinations</h3>
                    <p>Rank your preferences from 1st choice to 3rd choice. Consider surf quality, budget, culture, and adventure level.</p>
                    <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSc9C_W4hY3LXSGtHoa8duZolkOuOaAF9zFH7s0WOUXPF-Q1rQ/viewform?embedded=true" width="640" height="6484" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
                    </div>
                </div>
            </div>

            <div class="progress-tracker">
                <h3 style="color: #2c3e50; margin-bottom: 20px;">📊 Group Progress Tracker</h3>
                <div class="progress-item">
                    <div class="progress-icon pending">0/8</div>
                    <div class="progress-text">
                        <h4>Destination Voting</h4>
                        <p>Waiting for everyone to submit their top 3 choices</p>
                    </div>
                </div>
                <div class="progress-item">
                    <div class="progress-icon pending">0/8</div>
                    <div class="progress-text">
                        <h4>Budget & Date Preferences</h4>
                        <p>Need everyone's availability and budget range</p>
                    </div>
                </div>
                <div class="progress-item">
                    <div class="progress-icon pending">0/8</div>
                    <div class="progress-text">
                        <h4>Experience Survey</h4>
                        <p>Understanding everyone's surf level and interests</p>
                    </div>
                </div>
                <div class="progress-item">
                    <div class="progress-icon pending">0/8</div>
                    <div class="progress-text">
                        <h4>Trip Commitment</h4>
                        <p>Confirming participation and planning help</p>
                    </div>
                </div>
            </div>

            <div class="voting-deadline">
                ⏰ VOTING DEADLINE: January 15th, 2025 at 11:59 PM CST<br>
                <span style="font-size: 0.9em;">Final decision announcement: January 20th, 2025</span>
            </div>

            <div class="results-section">
                <h3>📊 Real-Time Results Dashboard</h3>
                <p style="font-size: 1.1em; margin: 15px 0;">Once everyone submits their preferences, we'll analyze the results and make data-driven decisions!</p>
                <div style="margin-top: 25px;">
                    <a href="https://docs.google.com/spreadsheets/d/1BxiMVs0XRA5nFMdKvBdBZjgmUUqptlbs74OgvE2upms/edit" class="link-button" target="_blank">📈 View Live Results Spreadsheet</a>
                    <a href="https://docs.google.com/forms/analytics" class="link-button" target="_blank">📊 Form Response Analytics</a>
                    <a href="https://docs.google.com/document/d/1example" class="link-button" target="_blank">📋 Decision Matrix Template</a>
                </div>
            </div>

            <div style="background: #fff3cd; color: #856404; padding: 25px; border-radius: 15px; margin: 30px 0; border-left: 5px solid #ffc107;">
                <h3 style="color: #856404; margin-bottom: 15px;">💡 Tips for Better Group Decision Making</h3>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin-top: 15px;">
                    <div>
                        <strong>🎯 Be Honest:</strong><br>
                        Share your real budget constraints and preferences
                    </div>
                    <div>
                        <strong>🤝 Be Flexible:</strong><br>
                        Consider compromise options that work for most
                    </div>
                    <div>
                        <strong>⏰ Be Timely:</strong><br>
                        Submit forms early to help with planning
                    </div>
                    <div>
                        <strong>🗣️ Be Vocal:</strong><br>
                        Ask questions in the group chat if unclear
                    </div>
                </div>
            </div>

            <div style="background: #e8f5e8; color: #2e7d32; padding: 25px; border-radius: 15px; margin: 30px 0; border-left: 5px solid #4caf50;">
                <h3 style="color: #2e7d32; margin-bottom: 15px;">🚀 What Happens After Voting</h3>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 15px; margin-top: 15px;">
                    <div>
                        <strong>📊 January 16-19:</strong><br>
                        Analyze all responses, create decision matrix
                    </div>
                    <div>
                        <strong>🎯 January 20:</strong><br>
                        Announce final destination choice
                    </div>
                    <div>
                        <strong>✈️ January 21-25:</strong><br>
                        Book flights as a group for best rates
                    </div>
                    <div>
                        <strong>🏠 January 26-31:</strong><br>
                        Reserve accommodations and plan activities
                    </div>
                </div>
            </div>

            <div class="urgent-notice">
                🎉 THE ADVENTURE STARTS WITH YOUR VOTE! 🎉<br>
                <span style="font-size: 0.9em;">Every vote counts - help make this the trip of a lifetime!</span>
            </div>

            <div style="text-align: center; margin-top: 40px;">
                <h3>📞 Questions or Technical Issues?</h3>
                <p style="color: #666; margin: 15px 0;">Contact the trip coordinator if you have any problems with the forms</p>
                <div style="margin-top: 20px;">
                    <a href="mailto:epic.surf.trip.2025@gmail.com" class="link-button" target="_blank">📧 Email Trip Coordinator</a>
                    <a href="https://wa.me/15551234567" class="link-button" target="_blank">💬 WhatsApp Support</a>
                    <a href="tel:+15551234567" class="link-button" target="_blank">📞 Call for Help</a>
                </div>
            </div>
        </div>
    </div>

    <script>
        // Update progress tracker based on form submissions (this would be connected to actual Google Forms responses)
        function updateProgress() {
            // This is a placeholder - in a real implementation, this would pull from Google Sheets API
            const totalPeople = 8;
            const responses = {
                destinations: 0, // Would be pulled from actual form responses
                budget: 0,       // Would be pulled from actual form responses  
                experience: 0,   // Would be pulled from actual form responses
                commitment: 0    // Would be pulled from actual form responses
            };

            Object.keys(responses).forEach(formType => {
                const icon = document.querySelector(`.progress-item:nth-child(${Object.keys(responses).indexOf(formType) + 1}) .progress-icon`);
                const count = responses[formType];
                
                icon.textContent = `${count}/${totalPeople}`;
                
                if (count === totalPeople) {
                    icon.classList.remove('pending');
                    icon.classList.add('complete');
                }
            });
        }

        // Initialize on page load
        window.addEventListener('load', function() {
            updateProgress();
            
            // Set up periodic updates (in real implementation, this would be connected to Google Forms)
            setInterval(updateProgress, 30000); // Update every 30 seconds
        });
    </script>
</body>
</html>
