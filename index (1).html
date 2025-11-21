<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced Calculator Pro</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjs/13.1.1/math.js"></script>
    <script src="https://cdn.plot.ly/plotly-2.27.0.min.js"></script>
    <style>
        :root {
            --color-cream-50: #fcfcf9;
            --color-cream-100: #fffffd;
            --color-gray-200: #f5f5f5;
            --color-gray-300: #a7a9a9;
            --color-slate-500: #626c71;
            --color-charcoal-700: #1f2121;
            --color-charcoal-800: #262828;
            --color-teal-300: #32b8c6;
            --color-teal-500: #21808d;
            --color-teal-600: #1d7480;
            --color-red-400: #ff5459;
            --color-red-500: #c0152f;
            --color-orange-400: #e68161;
            --color-brown-600-rgb: 94, 82, 64;
            --color-teal-500-rgb: 33, 128, 141;
            --color-slate-900-rgb: 19, 52, 59;
            --color-gray-400-rgb: 119, 124, 124;
            --color-teal-300-rgb: 50, 184, 198;
            
            --color-background: var(--color-cream-50);
            --color-surface: var(--color-cream-100);
            --color-text: #134252;
            --color-text-secondary: var(--color-slate-500);
            --color-primary: var(--color-teal-500);
            --color-primary-hover: var(--color-teal-600);
            --color-secondary: rgba(var(--color-brown-600-rgb), 0.12);
            --color-secondary-hover: rgba(var(--color-brown-600-rgb), 0.2);
            --color-border: rgba(var(--color-brown-600-rgb), 0.2);
            --color-error: var(--color-red-500);
            --color-success: var(--color-teal-500);
            --color-warning: var(--color-orange-400);
            --color-btn-primary-text: var(--color-cream-100);
        }

        @media (prefers-color-scheme: dark) {
            :root {
                --color-background: var(--color-charcoal-700);
                --color-surface: var(--color-charcoal-800);
                --color-text: var(--color-gray-200);
                --color-text-secondary: rgba(var(--color-gray-300), 0.7);
                --color-primary: var(--color-teal-300);
                --color-primary-hover: #29a5b1;
                --color-secondary: rgba(var(--color-gray-400-rgb), 0.15);
                --color-secondary-hover: rgba(var(--color-gray-400-rgb), 0.25);
                --color-border: rgba(var(--color-gray-400-rgb), 0.3);
                --color-error: var(--color-red-400);
                --color-success: var(--color-teal-300);
                --color-btn-primary-text: #134252;
            }
        }

        body.dark-mode {
            --color-background: var(--color-charcoal-700);
            --color-surface: var(--color-charcoal-800);
            --color-text: var(--color-gray-200);
            --color-text-secondary: rgba(var(--color-gray-300), 0.7);
            --color-primary: var(--color-teal-300);
            --color-primary-hover: #29a5b1;
            --color-secondary: rgba(var(--color-gray-400-rgb), 0.15);
            --color-secondary-hover: rgba(var(--color-gray-400-rgb), 0.25);
            --color-border: rgba(var(--color-gray-400-rgb), 0.3);
            --color-error: var(--color-red-400);
            --color-success: var(--color-teal-300);
            --color-btn-primary-text: #134252;
        }

        body.light-mode {
            --color-background: var(--color-cream-50);
            --color-surface: var(--color-cream-100);
            --color-text: #134252;
            --color-text-secondary: var(--color-slate-500);
            --color-primary: var(--color-teal-500);
            --color-primary-hover: var(--color-teal-600);
            --color-secondary: rgba(var(--color-brown-600-rgb), 0.12);
            --color-secondary-hover: rgba(var(--color-brown-600-rgb), 0.2);
            --color-border: rgba(var(--color-brown-600-rgb), 0.2);
            --color-error: var(--color-red-500);
            --color-success: var(--color-teal-500);
            --color-warning: var(--color-orange-400);
            --color-btn-primary-text: var(--color-cream-100);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            background: var(--color-background);
            color: var(--color-text);
            overflow-x: hidden;
        }

        .app-container {
            max-width: 480px;
            margin: 0 auto;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            background: var(--color-surface);
        }

        /* Header */
        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 16px;
            border-bottom: 1px solid var(--color-border);
            background: var(--color-surface);
        }

        .header-left {
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .header-right {
            display: flex;
            gap: 12px;
        }

        .icon-btn {
            background: none;
            border: none;
            color: var(--color-text);
            font-size: 20px;
            cursor: pointer;
            padding: 8px;
            border-radius: 8px;
            transition: background 0.2s;
        }

        .icon-btn:hover {
            background: var(--color-secondary);
        }

        .logo {
            font-size: 18px;
            font-weight: 600;
            color: var(--color-text);
        }

        /* Display Area */
        .display-area {
            padding: 24px 16px;
            background: var(--color-surface);
        }

        .history-preview {
            font-size: 14px;
            color: var(--color-text-secondary);
            margin-bottom: 12px;
            min-height: 20px;
        }

        .expression-container {
            background: var(--color-background);
            border: 1px solid var(--color-border);
            border-radius: 12px;
            padding: 16px;
            min-height: 60px;
            margin-bottom: 12px;
            overflow-x: auto;
            overflow-y: hidden;
        }

        .expression-input {
            font-size: 24px;
            color: var(--color-text);
            word-break: break-all;
            user-select: text;
        }

        .result-display {
            font-size: 42px;
            font-weight: 600;
            color: var(--color-primary);
            text-align: right;
            min-height: 50px;
        }

        .error-display {
            color: var(--color-error);
            font-size: 16px;
        }

        /* Function Bar */
        .function-bar {
            display: flex;
            gap: 8px;
            padding: 12px 16px;
            background: var(--color-background);
            overflow-x: auto;
            border-bottom: 1px solid var(--color-border);
        }

        .function-bar::-webkit-scrollbar {
            height: 4px;
        }

        .function-bar::-webkit-scrollbar-thumb {
            background: var(--color-border);
            border-radius: 4px;
        }

        .func-btn {
            padding: 8px 16px;
            background: var(--color-secondary);
            border: 1px solid var(--color-border);
            border-radius: 8px;
            color: var(--color-text);
            font-size: 14px;
            cursor: pointer;
            white-space: nowrap;
            transition: all 0.2s;
        }

        .func-btn:hover {
            background: var(--color-secondary-hover);
        }

        .func-btn:active {
            transform: scale(0.95);
        }

        /* Keypad */
        .keypad {
            flex: 1;
            padding: 16px;
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            grid-gap: 12px;
        }

        .btn {
            min-height: 64px;
            border: 1px solid var(--color-border);
            border-radius: 12px;
            font-size: 20px;
            font-weight: 500;
            cursor: pointer;
            transition: all 0.15s cubic-bezier(0.16, 1, 0.3, 1);
            display: flex;
            align-items: center;
            justify-content: center;
            user-select: none;
        }

        .btn:active {
            transform: scale(0.95);
        }

        .btn-number {
            background: var(--color-surface);
            color: var(--color-text);
            border: 1px solid var(--color-border);
        }

        .btn-number:hover {
            background: var(--color-secondary);
        }

        .btn-operation {
            background: var(--color-primary);
            color: var(--color-btn-primary-text);
            border: none;
            font-weight: 600;
        }

        .btn-operation:hover {
            background: var(--color-primary-hover);
        }

        .btn-function {
            background: var(--color-secondary);
            color: var(--color-text);
        }

        .btn-function:hover {
            background: var(--color-secondary-hover);
        }

        .btn-clear {
            background: rgba(192, 21, 47, 0.1);
            color: var(--color-error);
            border-color: var(--color-error);
        }

        .btn-clear:hover {
            background: rgba(192, 21, 47, 0.2);
        }

        .btn-equals {
            background: var(--color-success);
            color: var(--color-btn-primary-text);
            border: none;
            font-size: 24px;
        }

        .btn-equals:hover {
            opacity: 0.9;
        }

        .btn-zero {
            grid-column: span 1;
        }

        /* Mode Switcher */
        .mode-switcher {
            display: flex;
            border-top: 1px solid var(--color-border);
            background: var(--color-surface);
            overflow-x: auto;
        }

        .mode-tab {
            flex: 1;
            min-width: 80px;
            padding: 16px 12px;
            background: none;
            border: none;
            color: var(--color-text-secondary);
            font-size: 13px;
            cursor: pointer;
            transition: all 0.2s;
            border-bottom: 3px solid transparent;
        }

        .mode-tab:hover {
            background: var(--color-secondary);
        }

        .mode-tab.active {
            color: var(--color-primary);
            border-bottom-color: var(--color-primary);
            font-weight: 600;
        }

        /* History Panel */
        .history-panel {
            position: fixed;
            top: 0;
            right: -100%;
            width: 90%;
            max-width: 400px;
            height: 100vh;
            background: var(--color-surface);
            box-shadow: -4px 0 16px rgba(0, 0, 0, 0.1);
            transition: right 0.3s cubic-bezier(0.16, 1, 0.3, 1);
            z-index: 1000;
            display: flex;
            flex-direction: column;
        }

        .history-panel.open {
            right: 0;
        }

        .history-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 16px;
            border-bottom: 1px solid var(--color-border);
        }

        .history-header h3 {
            font-size: 18px;
            color: var(--color-text);
        }

        .history-list {
            flex: 1;
            overflow-y: auto;
            padding: 16px;
        }

        .history-item {
            padding: 12px;
            background: var(--color-background);
            border: 1px solid var(--color-border);
            border-radius: 8px;
            margin-bottom: 8px;
            cursor: pointer;
            transition: all 0.2s;
        }

        .history-item:hover {
            background: var(--color-secondary);
        }

        .history-expression {
            font-size: 14px;
            color: var(--color-text);
            margin-bottom: 4px;
        }

        .history-result {
            font-size: 16px;
            font-weight: 600;
            color: var(--color-primary);
        }

        .history-time {
            font-size: 12px;
            color: var(--color-text-secondary);
            margin-top: 4px;
        }

        /* Graph Mode */
        .graph-container {
            display: none;
            padding: 16px;
            background: var(--color-surface);
        }

        .graph-container.active {
            display: block;
        }

        .graph-input {
            width: 100%;
            padding: 12px;
            font-size: 16px;
            border: 1px solid var(--color-border);
            border-radius: 8px;
            background: var(--color-background);
            color: var(--color-text);
            margin-bottom: 12px;
        }

        #plotArea {
            width: 100%;
            height: 400px;
            background: var(--color-background);
            border-radius: 12px;
            border: 1px solid var(--color-border);
        }

        /* Voice Input */
        .voice-panel {
            position: fixed;
            bottom: -100%;
            left: 0;
            right: 0;
            background: var(--color-surface);
            border-top: 1px solid var(--color-border);
            padding: 24px;
            text-align: center;
            transition: bottom 0.3s cubic-bezier(0.16, 1, 0.3, 1);
            z-index: 1000;
        }

        .voice-panel.open {
            bottom: 0;
        }

        .voice-wave {
            width: 100px;
            height: 100px;
            margin: 0 auto 16px;
            background: var(--color-primary);
            border-radius: 50%;
            animation: pulse 1.5s ease-in-out infinite;
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); opacity: 0.6; }
            50% { transform: scale(1.1); opacity: 1; }
        }

        .voice-text {
            font-size: 18px;
            color: var(--color-text);
            margin-bottom: 12px;
        }

        .voice-transcript {
            font-size: 16px;
            color: var(--color-text-secondary);
            min-height: 24px;
        }

        /* Converter Mode */
        .converter-container {
            display: none;
            padding: 16px;
        }

        .converter-container.active {
            display: block;
        }

        .converter-group {
            margin-bottom: 16px;
        }

        .converter-group label {
            display: block;
            font-size: 14px;
            color: var(--color-text);
            margin-bottom: 8px;
        }

        .converter-input-group {
            display: flex;
            gap: 8px;
        }

        .converter-input-group input {
            flex: 1;
            padding: 12px;
            font-size: 16px;
            border: 1px solid var(--color-border);
            border-radius: 8px;
            background: var(--color-background);
            color: var(--color-text);
        }

        .converter-input-group select {
            padding: 12px;
            border: 1px solid var(--color-border);
            border-radius: 8px;
            background: var(--color-background);
            color: var(--color-text);
            font-size: 16px;
        }

        .converter-swap {
            text-align: center;
            margin: 12px 0;
        }

        .swap-btn {
            background: var(--color-secondary);
            border: 1px solid var(--color-border);
            border-radius: 50%;
            width: 40px;
            height: 40px;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            transition: all 0.2s;
        }

        .swap-btn:hover {
            background: var(--color-secondary-hover);
            transform: rotate(180deg);
        }

        /* Settings Panel */
        .settings-panel {
            position: fixed;
            top: 0;
            left: -100%;
            width: 90%;
            max-width: 400px;
            height: 100vh;
            background: var(--color-surface);
            box-shadow: 4px 0 16px rgba(0, 0, 0, 0.1);
            transition: left 0.3s cubic-bezier(0.16, 1, 0.3, 1);
            z-index: 1000;
            overflow-y: auto;
        }

        .settings-panel.open {
            left: 0;
        }

        .settings-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 16px;
            border-bottom: 1px solid var(--color-border);
            position: sticky;
            top: 0;
            background: var(--color-surface);
        }

        .settings-content {
            padding: 16px;
        }

        .setting-group {
            margin-bottom: 24px;
        }

        .setting-group h4 {
            font-size: 16px;
            color: var(--color-text);
            margin-bottom: 12px;
        }

        .setting-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 12px;
            background: var(--color-background);
            border-radius: 8px;
            margin-bottom: 8px;
        }

        .setting-label {
            font-size: 14px;
            color: var(--color-text);
        }

        .toggle-switch {
            position: relative;
            width: 48px;
            height: 24px;
            background: var(--color-border);
            border-radius: 12px;
            cursor: pointer;
            transition: background 0.3s;
        }

        .toggle-switch.active {
            background: var(--color-primary);
        }

        .toggle-switch::after {
            content: '';
            position: absolute;
            top: 2px;
            left: 2px;
            width: 20px;
            height: 20px;
            background: white;
            border-radius: 50%;
            transition: left 0.3s;
        }

        .toggle-switch.active::after {
            left: 26px;
        }

        .backdrop {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(0, 0, 0, 0.5);
            opacity: 0;
            pointer-events: none;
            transition: opacity 0.3s;
            z-index: 999;
        }

        .backdrop.active {
            opacity: 1;
            pointer-events: all;
        }

        @media (min-width: 768px) {
            .app-container {
                max-width: 600px;
                margin-top: 24px;
                border-radius: 24px;
                box-shadow: 0 10px 40px rgba(0, 0, 0, 0.1);
            }
        }
    </style>
</head>
<body>
    <div class="app-container">
        <!-- Header -->
        <div class="header">
            <div class="header-left">
                <button class="icon-btn" id="menuBtn">☰</button>
                <div class="logo">Calculator Pro</div>
            </div>
            <div class="header-right">
                <button class="icon-btn" id="voiceBtn">🎤</button>
                <button class="icon-btn" id="historyBtn">📊</button>
            </div>
        </div>

        <!-- Display Area -->
        <div class="display-area">
            <div class="history-preview" id="historyPreview"></div>
            <div class="expression-container">
                <div class="expression-input" id="expressionDisplay">0</div>
            </div>
            <div class="result-display" id="resultDisplay"></div>
        </div>

        <!-- Function Bar -->
        <div class="function-bar" id="functionBar">
            <button class="func-btn" data-func="sin">sin</button>
            <button class="func-btn" data-func="cos">cos</button>
            <button class="func-btn" data-func="tan">tan</button>
            <button class="func-btn" data-func="sqrt">√</button>
            <button class="func-btn" data-func="^">x²</button>
            <button class="func-btn" data-func="pi">π</button>
            <button class="func-btn" data-func="log">log</button>
            <button class="func-btn" data-func="ln">ln</button>
        </div>

        <!-- Graph Mode -->
        <div class="graph-container" id="graphMode">
            <input type="text" class="graph-input" id="graphInput" placeholder="Enter function: x^2, sin(x), etc.">
            <div id="plotArea"></div>
        </div>

        <!-- Converter Mode -->
        <div class="converter-container" id="converterMode">
            <div class="converter-group">
                <label>From:</label>
                <div class="converter-input-group">
                    <input type="number" id="fromValue" value="1">
                    <select id="fromUnit">
                        <option value="m">Meters</option>
                        <option value="km">Kilometers</option>
                        <option value="mi">Miles</option>
                        <option value="ft">Feet</option>
                    </select>
                </div>
            </div>
            <div class="converter-swap">
                <button class="swap-btn" id="swapBtn">⇅</button>
            </div>
            <div class="converter-group">
                <label>To:</label>
                <div class="converter-input-group">
                    <input type="number" id="toValue" readonly>
                    <select id="toUnit">
                        <option value="m">Meters</option>
                        <option value="km">Kilometers</option>
                        <option value="mi">Miles</option>
                        <option value="ft">Feet</option>
                    </select>
                </div>
            </div>
        </div>

        <!-- Keypad -->
        <div class="keypad" id="keypad">
            <button class="btn btn-clear" data-action="clear">AC</button>
            <button class="btn btn-function" data-action="parentheses">()</button>
            <button class="btn btn-function" data-action="percent">%</button>
            <button class="btn btn-operation" data-value="/">÷</button>
            
            <button class="btn btn-number" data-value="7">7</button>
            <button class="btn btn-number" data-value="8">8</button>
            <button class="btn btn-number" data-value="9">9</button>
            <button class="btn btn-operation" data-value="*">×</button>
            
            <button class="btn btn-number" data-value="4">4</button>
            <button class="btn btn-number" data-value="5">5</button>
            <button class="btn btn-number" data-value="6">6</button>
            <button class="btn btn-operation" data-value="-">−</button>
            
            <button class="btn btn-number" data-value="1">1</button>
            <button class="btn btn-number" data-value="2">2</button>
            <button class="btn btn-number" data-value="3">3</button>
            <button class="btn btn-operation" data-value="+">+</button>
            
            <button class="btn btn-number btn-zero" data-value="0">0</button>
            <button class="btn btn-number" data-value=".">.</button>
            <button class="btn btn-function" data-action="backspace">⌫</button>
            <button class="btn btn-equals" data-action="equals">=</button>
        </div>

        <!-- Mode Switcher -->
        <div class="mode-switcher">
            <button class="mode-tab active" data-mode="basic">Basic</button>
            <button class="mode-tab" data-mode="scientific">Scientific</button>
            <button class="mode-tab" data-mode="graph">Graph</button>
            <button class="mode-tab" data-mode="converter">Convert</button>
        </div>
    </div>

    <!-- History Panel -->
    <div class="history-panel" id="historyPanel">
        <div class="history-header">
            <h3>History</h3>
            <button class="icon-btn" id="closeHistoryBtn">×</button>
        </div>
        <div class="history-list" id="historyList">
            <!-- History items will be added here -->
        </div>
    </div>

    <!-- Settings Panel -->
    <div class="settings-panel" id="settingsPanel">
        <div class="settings-header">
            <h3>Settings</h3>
            <button class="icon-btn" id="closeSettingsBtn">×</button>
        </div>
        <div class="settings-content">
            <div class="setting-group">
                <h4>Calculation</h4>
                <div class="setting-item">
                    <span class="setting-label">Angle Mode</span>
                    <select id="angleMode" style="padding: 8px; border-radius: 6px; border: 1px solid var(--color-border); background: var(--color-background); color: var(--color-text);">
                        <option value="deg">Degrees</option>
                        <option value="rad">Radians</option>
                    </select>
                </div>
            </div>
            <div class="setting-group">
                <h4>Appearance</h4>
                <div class="setting-item">
                    <span class="setting-label">Haptic Feedback</span>
                    <div class="toggle-switch active" id="hapticToggle"></div>
                </div>
                <div class="setting-item">
                    <span class="setting-label">Sound Effects</span>
                    <div class="toggle-switch active" id="soundToggle"></div>
                </div>
                <div class="setting-item">
                    <span class="setting-label">Theme</span>
                    <select id="themeSelect" style="padding: 8px; border-radius: 6px; border: 1px solid var(--color-border); background: var(--color-background); color: var(--color-text);">
                        <option value="auto">Auto</option>
                        <option value="light">Light</option>
                        <option value="dark">Dark</option>
                    </select>
                </div>
            </div>
        </div>
    </div>

    <!-- Voice Panel -->
    <div class="voice-panel" id="voicePanel">
        <div class="voice-wave"></div>
        <div class="voice-text">Listening...</div>
        <div class="voice-transcript" id="voiceTranscript">Say your calculation</div>
        <button class="icon-btn" id="closeVoiceBtn" style="margin-top: 16px;">×</button>
    </div>

    <!-- Backdrop -->
    <div class="backdrop" id="backdrop"></div>

    <script>
        // Calculator State
        let state = {
            expression: '',
            result: '',
            history: [],
            mode: 'basic',
            angleMode: 'deg',
            hapticEnabled: true,
            soundEnabled: true,
            theme: 'auto'
        };

        // DOM Elements
        const expressionDisplay = document.getElementById('expressionDisplay');
        const resultDisplay = document.getElementById('resultDisplay');
        const historyPreview = document.getElementById('historyPreview');
        const historyPanel = document.getElementById('historyPanel');
        const historyList = document.getElementById('historyList');
        const settingsPanel = document.getElementById('settingsPanel');
        const voicePanel = document.getElementById('voicePanel');
        const backdrop = document.getElementById('backdrop');
        const keypad = document.getElementById('keypad');
        const graphMode = document.getElementById('graphMode');
        const converterMode = document.getElementById('converterMode');
        const functionBar = document.getElementById('functionBar');

        // Load saved state
        function loadState() {
            const saved = localStorage.getItem('calculatorState');
            if (saved) {
                const parsed = JSON.parse(saved);
                state = { ...state, ...parsed };
                updateDisplay();
                applyTheme(state.theme || 'auto');
            }
        }

        // Apply theme
        function applyTheme(theme) {
            state.theme = theme;
            const body = document.body;
            const themeBtn = document.getElementById('themeBtn');
            
            body.classList.remove('dark-mode', 'light-mode');
            
            if (theme === 'dark') {
                body.classList.add('dark-mode');
                themeBtn.textContent = '☀️';
            } else if (theme === 'light') {
                body.classList.add('light-mode');
                themeBtn.textContent = '🌙';
            } else {
                // Auto mode
                const prefersDark = window.matchMedia('(prefers-color-scheme: dark)').matches;
                themeBtn.textContent = prefersDark ? '☀️' : '🌙';
            }
            
            saveState();
        }

        // Save state
        function saveState() {
            localStorage.setItem('calculatorState', JSON.stringify(state));
        }

        // Update display
        function updateDisplay() {
            expressionDisplay.textContent = state.expression || '0';
            resultDisplay.textContent = state.result || '';
            if (state.history.length > 0) {
                const last = state.history[0];
                historyPreview.textContent = `${last.expression} = ${last.result}`;
            }
        }

        // Haptic feedback
        function haptic() {
            if (state.hapticEnabled && navigator.vibrate) {
                navigator.vibrate(10);
            }
        }

        // Sound feedback
        function playSound() {
            if (state.soundEnabled) {
                const audioContext = new (window.AudioContext || window.webkitAudioContext)();
                const oscillator = audioContext.createOscillator();
                const gainNode = audioContext.createGain();
                oscillator.connect(gainNode);
                gainNode.connect(audioContext.destination);
                oscillator.frequency.value = 800;
                gainNode.gain.value = 0.1;
                oscillator.start();
                oscillator.stop(audioContext.currentTime + 0.05);
            }
        }

        // Handle button clicks
        keypad.addEventListener('click', (e) => {
            const btn = e.target.closest('.btn');
            if (!btn) return;

            haptic();
            playSound();

            const value = btn.dataset.value;
            const action = btn.dataset.action;

            if (value) {
                state.expression += value;
                updateDisplay();
            } else if (action) {
                handleAction(action);
            }

            saveState();
        });

        // Handle actions
        function handleAction(action) {
            switch (action) {
                case 'clear':
                    state.expression = '';
                    state.result = '';
                    updateDisplay();
                    break;
                case 'backspace':
                    state.expression = state.expression.slice(0, -1);
                    updateDisplay();
                    break;
                case 'equals':
                    calculate();
                    break;
                case 'parentheses':
                    const openCount = (state.expression.match(/\(/g) || []).length;
                    const closeCount = (state.expression.match(/\)/g) || []).length;
                    state.expression += openCount > closeCount ? ')' : '(';
                    updateDisplay();
                    break;
                case 'percent':
                    state.expression += '%';
                    updateDisplay();
                    break;
            }
        }

        // Calculate result
        function calculate() {
            try {
                let expr = state.expression;
                
                // Handle percentage
                expr = expr.replace(/(\d+\.?\d*)%/g, '($1/100)');
                
                // Configure math.js
                const config = {
                    number: 'BigNumber',
                    precision: 64
                };
                
                // Parse and evaluate
                const result = math.evaluate(expr, { deg: state.angleMode === 'deg' ? 180/Math.PI : 1 });
                
                // Format result
                let formattedResult = typeof result === 'object' ? result.toString() : result.toString();
                
                // Round to reasonable precision for display
                if (!isNaN(formattedResult)) {
                    const num = parseFloat(formattedResult);
                    formattedResult = Math.abs(num) < 1e-10 ? '0' : 
                                    Math.abs(num) > 1e10 ? num.toExponential(6) :
                                    num.toString();
                }
                
                state.result = formattedResult;
                
                // Add to history
                state.history.unshift({
                    expression: state.expression,
                    result: formattedResult,
                    timestamp: Date.now()
                });
                
                // Keep only last 100 items
                state.history = state.history.slice(0, 100);
                
                updateDisplay();
                updateHistoryPanel();
                saveState();
                
            } catch (error) {
                resultDisplay.textContent = 'Error';
                resultDisplay.className = 'result-display error-display';
                setTimeout(() => {
                    resultDisplay.className = 'result-display';
                }, 2000);
            }
        }

        // Function buttons
        functionBar.addEventListener('click', (e) => {
            const btn = e.target.closest('.func-btn');
            if (!btn) return;
            
            haptic();
            playSound();
            
            const func = btn.dataset.func;
            
            switch (func) {
                case 'sin':
                case 'cos':
                case 'tan':
                case 'log':
                case 'ln':
                    state.expression += func + '(';
                    break;
                case 'sqrt':
                    state.expression += 'sqrt(';
                    break;
                case '^':
                    state.expression += '^2';
                    break;
                case 'pi':
                    state.expression += 'pi';
                    break;
            }
            
            updateDisplay();
            saveState();
        });

        // Mode switching
        document.querySelectorAll('.mode-tab').forEach(tab => {
            tab.addEventListener('click', () => {
                document.querySelectorAll('.mode-tab').forEach(t => t.classList.remove('active'));
                tab.classList.add('active');
                
                const mode = tab.dataset.mode;
                state.mode = mode;
                
                keypad.style.display = mode === 'basic' || mode === 'scientific' ? 'grid' : 'none';
                graphMode.classList.toggle('active', mode === 'graph');
                converterMode.classList.toggle('active', mode === 'converter');
                
                if (mode === 'scientific') {
                    // Show more advanced functions
                    functionBar.innerHTML = `
                        <button class="func-btn" data-func="sin">sin</button>
                        <button class="func-btn" data-func="cos">cos</button>
                        <button class="func-btn" data-func="tan">tan</button>
                        <button class="func-btn" data-func="sqrt">√</button>
                        <button class="func-btn" data-func="^">x²</button>
                        <button class="func-btn" data-func="pi">π</button>
                        <button class="func-btn" data-func="log">log</button>
                        <button class="func-btn" data-func="ln">ln</button>
                        <button class="func-btn" data-func="exp">e^x</button>
                        <button class="func-btn" data-func="abs">|x|</button>
                    `;
                } else if (mode === 'basic') {
                    functionBar.innerHTML = `
                        <button class="func-btn" data-func="sin">sin</button>
                        <button class="func-btn" data-func="cos">cos</button>
                        <button class="func-btn" data-func="tan">tan</button>
                        <button class="func-btn" data-func="sqrt">√</button>
                        <button class="func-btn" data-func="^">x²</button>
                        <button class="func-btn" data-func="pi">π</button>
                        <button class="func-btn" data-func="log">log</button>
                        <button class="func-btn" data-func="ln">ln</button>
                    `;
                }
                
                saveState();
            });
        });

        // History panel
        document.getElementById('historyBtn').addEventListener('click', () => {
            historyPanel.classList.add('open');
            backdrop.classList.add('active');
        });

        document.getElementById('closeHistoryBtn').addEventListener('click', () => {
            historyPanel.classList.remove('open');
            backdrop.classList.remove('active');
        });

        function updateHistoryPanel() {
            historyList.innerHTML = '';
            state.history.forEach(item => {
                const div = document.createElement('div');
                div.className = 'history-item';
                div.innerHTML = `
                    <div class="history-expression">${item.expression}</div>
                    <div class="history-result">= ${item.result}</div>
                    <div class="history-time">${new Date(item.timestamp).toLocaleTimeString()}</div>
                `;
                div.addEventListener('click', () => {
                    state.expression = item.expression;
                    state.result = item.result;
                    updateDisplay();
                    historyPanel.classList.remove('open');
                    backdrop.classList.remove('active');
                });
                historyList.appendChild(div);
            });
        }

        // Settings panel
        document.getElementById('menuBtn').addEventListener('click', () => {
            settingsPanel.classList.add('open');
            backdrop.classList.add('active');
        });

        document.getElementById('closeSettingsBtn').addEventListener('click', () => {
            settingsPanel.classList.remove('open');
            backdrop.classList.remove('active');
        });

        // Settings toggles
        document.getElementById('hapticToggle').addEventListener('click', function() {
            this.classList.toggle('active');
            state.hapticEnabled = this.classList.contains('active');
            saveState();
        });

        document.getElementById('soundToggle').addEventListener('click', function() {
            this.classList.toggle('active');
            state.soundEnabled = this.classList.contains('active');
            saveState();
        });

        document.getElementById('angleMode').addEventListener('change', function() {
            state.angleMode = this.value;
            saveState();
        });

        // Theme toggle
        document.getElementById('themeBtn').addEventListener('click', () => {
            const themes = ['auto', 'light', 'dark'];
            const currentIndex = themes.indexOf(state.theme || 'auto');
            const nextTheme = themes[(currentIndex + 1) % themes.length];
            applyTheme(nextTheme);
        });

        // Voice input
        document.getElementById('voiceBtn').addEventListener('click', () => {
            if ('webkitSpeechRecognition' in window || 'SpeechRecognition' in window) {
                voicePanel.classList.add('open');
                backdrop.classList.add('active');
                startVoiceRecognition();
            } else {
                alert('Voice recognition is not supported in your browser. Please use Chrome.');
            }
        });

        document.getElementById('closeVoiceBtn').addEventListener('click', () => {
            voicePanel.classList.remove('open');
            backdrop.classList.remove('active');
            if (window.recognition) {
                window.recognition.stop();
            }
        });

        function startVoiceRecognition() {
            const SpeechRecognition = window.SpeechRecognition || window.webkitSpeechRecognition;
            const recognition = new SpeechRecognition();
            window.recognition = recognition;
            
            recognition.continuous = false;
            recognition.interimResults = true;
            recognition.lang = 'en-US';
            
            recognition.onresult = (event) => {
                const transcript = event.results[0][0].transcript.toLowerCase();
                document.getElementById('voiceTranscript').textContent = transcript;
                
                if (event.results[0].isFinal) {
                    processVoiceCommand(transcript);
                }
            };
            
            recognition.onerror = (event) => {
                console.error('Speech recognition error:', event.error);
            };
            
            recognition.start();
        }

        function processVoiceCommand(text) {
            // Convert speech to math expression
            let expr = text
                .replace(/plus/g, '+')
                .replace(/minus/g, '-')
                .replace(/times/g, '*')
                .replace(/multiplied by/g, '*')
                .replace(/divided by/g, '/')
                .replace(/squared/g, '^2')
                .replace(/cubed/g, '^3')
                .replace(/square root of/g, 'sqrt(')
                .replace(/sine of/g, 'sin(')
                .replace(/cosine of/g, 'cos(')
                .replace(/tangent of/g, 'tan(')
                .replace(/log of/g, 'log(')
                .replace(/percent/g, '%');
            
            // Convert word numbers to digits
            const numbers = {
                'zero': '0', 'one': '1', 'two': '2', 'three': '3', 'four': '4',
                'five': '5', 'six': '6', 'seven': '7', 'eight': '8', 'nine': '9',
                'ten': '10', 'twenty': '20', 'thirty': '30', 'forty': '40',
                'fifty': '50', 'sixty': '60', 'seventy': '70', 'eighty': '80', 'ninety': '90',
                'hundred': '100', 'thousand': '1000'
            };
            
            Object.keys(numbers).forEach(word => {
                expr = expr.replace(new RegExp(word, 'g'), numbers[word]);
            });
            
            state.expression = expr.replace(/[^\d+\-*/(). sqrt^sincostan%]/g, '');
            updateDisplay();
            
            setTimeout(() => {
                calculate();
                voicePanel.classList.remove('open');
                backdrop.classList.remove('active');
            }, 500);
        }

        // Graphing
        document.getElementById('graphInput').addEventListener('change', function() {
            plotFunction(this.value);
        });

        function plotFunction(funcStr) {
            try {
                const xValues = [];
                const yValues = [];
                
                for (let x = -10; x <= 10; x += 0.1) {
                    xValues.push(x);
                    try {
                        const y = math.evaluate(funcStr, { x: x });
                        yValues.push(typeof y === 'object' ? parseFloat(y.toString()) : y);
                    } catch {
                        yValues.push(null);
                    }
                }
                
                const trace = {
                    x: xValues,
                    y: yValues,
                    type: 'scatter',
                    mode: 'lines',
                    line: { color: '#21808d', width: 2 }
                };
                
                const layout = {
                    xaxis: { title: 'x', zeroline: true, gridcolor: '#e0e0e0' },
                    yaxis: { title: 'y', zeroline: true, gridcolor: '#e0e0e0' },
                    plot_bgcolor: 'var(--color-background)',
                    paper_bgcolor: 'var(--color-background)',
                    font: { color: 'var(--color-text)' },
                    margin: { t: 20, r: 20, b: 40, l: 40 }
                };
                
                Plotly.newPlot('plotArea', [trace], layout, { responsive: true });
            } catch (error) {
                console.error('Plotting error:', error);
            }
        }

        // Unit converter
        const conversions = {
            m: 1,
            km: 0.001,
            mi: 0.000621371,
            ft: 3.28084
        };

        function convert() {
            const fromVal = parseFloat(document.getElementById('fromValue').value);
            const fromUnit = document.getElementById('fromUnit').value;
            const toUnit = document.getElementById('toUnit').value;
            
            const meters = fromVal / conversions[fromUnit];
            const result = meters * conversions[toUnit];
            
            document.getElementById('toValue').value = result.toFixed(4);
        }

        document.getElementById('fromValue').addEventListener('input', convert);
        document.getElementById('fromUnit').addEventListener('change', convert);
        document.getElementById('toUnit').addEventListener('change', convert);

        document.getElementById('swapBtn').addEventListener('click', () => {
            const fromUnit = document.getElementById('fromUnit');
            const toUnit = document.getElementById('toUnit');
            const temp = fromUnit.value;
            fromUnit.value = toUnit.value;
            toUnit.value = temp;
            convert();
        });

        // Backdrop click
        backdrop.addEventListener('click', () => {
            historyPanel.classList.remove('open');
            settingsPanel.classList.remove('open');
            voicePanel.classList.remove('open');
            backdrop.classList.remove('active');
        });

        // Keyboard support
        document.addEventListener('keydown', (e) => {
            if (e.key >= '0' && e.key <= '9') {
                state.expression += e.key;
                updateDisplay();
            } else if (['+', '-', '*', '/', '(', ')', '.'].includes(e.key)) {
                state.expression += e.key;
                updateDisplay();
            } else if (e.key === 'Enter') {
                calculate();
            } else if (e.key === 'Backspace') {
                state.expression = state.expression.slice(0, -1);
                updateDisplay();
            } else if (e.key === 'Escape') {
                state.expression = '';
                state.result = '';
                updateDisplay();
            }
            saveState();
        });

        // Theme select in settings
        document.getElementById('themeSelect').addEventListener('change', function() {
            applyTheme(this.value);
        });

        // Initialize
        loadState();
        updateHistoryPanel();
        convert();
        
        // Set theme select value
        if (document.getElementById('themeSelect')) {
            document.getElementById('themeSelect').value = state.theme || 'auto';
        }
    </script>
</body>
</html>
