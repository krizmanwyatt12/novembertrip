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
