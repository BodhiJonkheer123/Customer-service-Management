<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CS Quick Reference</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        
        .header {
            background: linear-gradient(135deg, #ff6b6b, #ffd93d);
            padding: 30px;
            text-align: center;
            color: white;
        }
        
        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }
        
        .search-container {
            padding: 30px;
            background: #f8f9fa;
            border-bottom: 1px solid #e9ecef;
        }
        
        .search-box {
            position: relative;
            max-width: 600px;
            margin: 0 auto;
        }
        
        #searchInput {
            width: 100%;
            padding: 15px 50px 15px 20px;
            font-size: 16px;
            border: 2px solid #ddd;
            border-radius: 50px;
            outline: none;
            transition: all 0.3s ease;
        }
        
        #searchInput:focus {
            border-color: #667eea;
            box-shadow: 0 0 0 3px rgba(102, 126, 234, 0.1);
        }
        
        .search-icon {
            position: absolute;
            right: 20px;
            top: 50%;
            transform: translateY(-50%);
            color: #999;
        }
        
        .categories {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 30px;
            padding: 30px;
        }
        
        .category {
            background: white;
            border-radius: 15px;
            border: 2px solid #e9ecef;
            overflow: hidden;
            transition: all 0.3s ease;
            animation: fadeIn 0.5s ease-out;
        }
        
        .category:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.1);
            border-color: #667eea;
        }
        
        .category-header {
            padding: 20px;
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            font-weight: bold;
            font-size: 1.2rem;
        }
        
        .scenario-list {
            padding: 0;
        }
        
        .scenario-item {
            padding: 15px 20px;
            border-bottom: 1px solid #f0f0f0;
            cursor: pointer;
            transition: all 0.2s ease;
            display: flex;
            align-items: center;
            justify-content: space-between;
            text-decoration: none;
            color: inherit;
        }
        
        .scenario-item:hover {
            background: linear-gradient(135deg, #667eea10, #764ba210);
            padding-left: 30px;
            transform: translateX(5px);
        }
        
        .scenario-item:active {
            transform: scale(0.98);
        }
        
        .scenario-item:last-child {
            border-bottom: none;
        }
        
        .scenario-text {
            flex: 1;
            font-size: 14px;
            color: #333;
        }
        
        .scenario-badge {
            background: #667eea;
            color: white;
            padding: 4px 8px;
            border-radius: 12px;
            font-size: 10px;
            font-weight: bold;
            margin-left: 10px;
        }
        
        .link-icon {
            background: #28a745;
            color: white;
            padding: 4px 6px;
            border-radius: 8px;
            font-size: 10px;
            margin-left: 8px;
            opacity: 1;
            transition: all 0.2s ease;
        }
        
        .scenario-item:hover .link-icon {
            opacity: 1;
            background: #20c997;
        }
        
        .external-link {
            color: #667eea;
            text-decoration: none;
            font-weight: 500;
        }
        
        .external-link:hover {
            text-decoration: underline;
        }
        
        .hidden {
            display: none;
        }
        
        .no-results {
            text-align: center;
            padding: 40px;
            color: #666;
            font-size: 18px;
        }
        
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        .stats {
            display: flex;
            justify-content: center;
            gap: 30px;
            padding: 20px;
            background: #f8f9fa;
            color: #666;
            font-size: 14px;
        }
        
        .stat-item {
            display: flex;
            align-items: center;
            gap: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🚀 Customer Service Quick Reference</h1>
            <p>Find the right template instantly</p>
        </div>
        
        <div class="search-container">
            <div class="search-box">
                <input type="text" id="searchInput" placeholder="Search scenarios, keywords, issues...">
                <span class="search-icon">🔍</span>
            </div>
        </div>
        
        <div class="categories" id="categoriesContainer">
            <div class="category" data-category="order-inquiry">
                <div class="category-header">📋 1. ORDER INQUIRY</div>
                <div class="scenario-list">
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a802a9a20e49d975ee619" class="scenario-item external-link" data-keywords="product question sizing no link name" target="_blank">
                        <span class="scenario-text">Product Question - No link or name provided</span>
                        <span class="scenario-badge">INFO</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80ef880cef08c1ba50d7" class="scenario-item external-link" data-keywords="order info no order number find customer" target="_blank">
                        <span class="scenario-text">Order Info - No order number provided</span>
                        <span class="scenario-badge">SEARCH</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a8000b6a6cd4de75f2fab" class="scenario-item external-link" data-keywords="no order found number information" target="_blank">
                        <span class="scenario-text">No order found with provided information</span>
                        <span class="scenario-badge">ERROR</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a800b9b3af9a1644a123f" class="scenario-item external-link" data-keywords="where is my package" target="_blank">
                        <span class="scenario-text">WHERE IS MY PACKAGE</span>
                        <span class="scenario-badge">TRACK</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80a6a16adf6506e9af39" class="scenario-item external-link" data-keywords="where is my package no tracking info" target="_blank">
                        <span class="scenario-text">WHERE IS MY PACKAGE - No tracking info</span>
                        <span class="scenario-badge">TRACK</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80239e49d117b7390b71" class="scenario-item external-link" data-keywords="where is my package with tracking" target="_blank">
                        <span class="scenario-text">WHERE IS MY PACKAGE - With tracking</span>
                        <span class="scenario-badge">TRACK</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80d6a2a6e5315c6c0a1f" class="scenario-item external-link" data-keywords="cancellation bad review social media" target="_blank">
                        <span class="scenario-text">Cancellation due to bad review from social media</span>
                        <span class="scenario-badge">CANCEL</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80dab73ac088ff18f1b4" class="scenario-item external-link" data-keywords="cancellation delayed processing 3 days" target="_blank">
                        <span class="scenario-text">Cancellation - Delayed processing (3+ days)</span>
                        <span class="scenario-badge">CANCEL</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a801798fbee3e7f523b64" class="scenario-item external-link" data-keywords="cancellation request 24 hours policy" target="_blank">
                        <span class="scenario-text">Cancellation request beyond 24 hours</span>
                        <span class="scenario-badge">POLICY</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80f2ab67d8658ef580ad" class="scenario-item external-link" data-keywords="cancellation 24 hours fulfilled in progress" target="_blank">
                        <span class="scenario-text">Cancellation 24h+ when fulfilled/in progress</span>
                        <span class="scenario-badge">POLICY</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a808fb61de3bdf7751668" class="scenario-item external-link" data-keywords="cancellation long delivery 10 days transit" target="_blank">
                        <span class="scenario-text">Cancellation - Long delivery (10+ days) in transit</span>
                        <span class="scenario-badge">CANCEL</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80f18c8ae4126c58a241" class="scenario-item external-link" data-keywords="change shipping address unfulfilled" target="_blank">
                        <span class="scenario-text">Change shipping address - Unfulfilled order</span>
                        <span class="scenario-badge">UPDATE</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80f79a35dc4aa553f5f5" class="scenario-item external-link" data-keywords="change shipping address already fulfilled tracking" target="_blank">
                        <span class="scenario-text">Change shipping address - Already fulfilled (with tracking)</span>
                        <span class="scenario-badge">POLICY</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80e89266ce94c13dadbd" class="scenario-item external-link" data-keywords="change shipping address already fulfilled no tracking" target="_blank">
                        <span class="scenario-text">Change shipping address - Already fulfilled (no tracking)</span>
                        <span class="scenario-badge">POLICY</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80958e2cc8c8b7797f44" class="scenario-item external-link" data-keywords="change color size order not fulfilled" target="_blank">
                        <span class="scenario-text">Change color or size - Order not fulfilled</span>
                        <span class="scenario-badge">UPDATE</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80f3a31def7d881ed766" class="scenario-item external-link" data-keywords="change color size order already fulfilled" target="_blank">
                        <span class="scenario-text">Change color or size - Order already fulfilled</span>
                        <span class="scenario-badge">POLICY</span>
                        <span class="link-icon">🔗</span>
                    </a>
                </div>
            </div>
            
            <div class="category" data-category="returns">
                <div class="category-header">↩️ 2. RETURNS</div>
                <div class="scenario-list">
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a8083bf94ed36ecf5427f" class="scenario-item external-link" data-keywords="return reason not provided" target="_blank">
                        <span class="scenario-text">Step 1: Return reason not provided</span>
                        <span class="scenario-badge">STEP 1</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80d5a712e4b4c3ed39e3" class="scenario-item external-link" data-keywords="return wrong address step 1" target="_blank">
                        <span class="scenario-text">Step 1B: Return - Wrong address provided</span>
                        <span class="scenario-badge">STEP 1B</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a8079868ff2d18c7ac890" class="scenario-item external-link" data-keywords="ask for photo evidence actual item" target="_blank">
                        <span class="scenario-text">Step 2: Ask for actual item photo</span>
                        <span class="scenario-badge">STEP 2</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80d8b584e57e23ea97d4" class="scenario-item external-link" data-keywords="refused to send photo return" target="_blank">
                        <span class="scenario-text">Step 2B: Customer refused to send photo</span>
                        <span class="scenario-badge">STEP 2B</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80379e85fd9e7af40099" class="scenario-item external-link" data-keywords="return information provided size issue offer replacement" target="_blank">
                        <span class="scenario-text">Step 3: Size issue - Offer replacement</span>
                        <span class="scenario-badge">STEP 3</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a8035a776d6423ca398a8" class="scenario-item external-link" data-keywords="offer 10% partial refund" target="_blank">
                        <span class="scenario-text">Step 5: Offer 10% partial refund</span>
                        <span class="scenario-badge">STEP 5</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80dc9552eea2a379d994" class="scenario-item external-link" data-keywords="20% partial refund return instruction" target="_blank">
                        <span class="scenario-text">Step 6: 20% partial refund + return instruction</span>
                        <span class="scenario-badge">STEP 6</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a809299dff17d2ad1a183" class="scenario-item external-link" data-keywords="re-offer 20% partial refund" target="_blank">
                        <span class="scenario-text">Step 7: Re-offer 20% partial refund</span>
                        <span class="scenario-badge">STEP 7</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a800ba0f6ce8434c7d466" class="scenario-item external-link" data-keywords="offer 30% partial refund maximum" target="_blank">
                        <span class="scenario-text">Step 8: Offer 30% partial refund (maximum)</span>
                        <span class="scenario-badge">STEP 8</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80159ac1f418d72a7658" class="scenario-item external-link" data-keywords="does not accept solution return offers refused pushback" target="_blank">
                        <span class="scenario-text">Step 9: Customer does not accept solution - Process return</span>
                        <span class="scenario-badge">STEP 9</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80239b51cda852aa5afd" class="scenario-item external-link" data-keywords="partial refund keep item" target="_blank">
                        <span class="scenario-text">Partial refund - Customer keeps item</span>
                        <span class="scenario-badge">REFUND</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80839862f8bcf0272cdc" class="scenario-item external-link" data-keywords="full refund purchase amount refunded" target="_blank">
                        <span class="scenario-text">Full purchase amount refunded</span>
                        <span class="scenario-badge">REFUND</span>
                        <span class="link-icon">🔗</span>
                    </a>
                </div>
            </div>
            
            <div class="category" data-category="damaged-wrong">
                <div class="category-header">📦 3. DAMAGED/WRONG ITEM</div>
                <div class="scenario-list">
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80aeb26efe44aa93fa71" class="scenario-item external-link" data-keywords="defect ask for photo step 1" target="_blank">
                        <span class="scenario-text">Step 1: Ask for photo (Defect)</span>
                        <span class="scenario-badge">STEP 1</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a808982aded11c953bd82" class="scenario-item external-link" data-keywords="defect offer new package replacement step 2" target="_blank">
                        <span class="scenario-text">Step 2: Offer new package (Defect replacement)</span>
                        <span class="scenario-badge">STEP 2</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a8095aecbdaa2af873538" class="scenario-item external-link" data-keywords="defect customer refused new package step 3" target="_blank">
                        <span class="scenario-text">Step 3: Customer refused new package (Defect)</span>
                        <span class="scenario-badge">STEP 3</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a8061a7c0c5dcafc8d144" class="scenario-item external-link" data-keywords="defect refused new package different item 100% refund step 4" target="_blank">
                        <span class="scenario-text">Step 4: Refused replacement & different item - 100% refund</span>
                        <span class="scenario-badge">REFUND</span>
                        <span class="link-icon">🔗</span>
                    </a>
                </div>
            </div>
            
            <div class="category" data-category="lost-in-transit">
                <div class="category-header">📍 4. ORDER LOST IN TRANSIT</div>
                <div class="scenario-list">
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80da83c7fe6013c816bf" class="scenario-item external-link" data-keywords="delivered not received step 1" target="_blank">
                        <span class="scenario-text">DELIVERED NOT RECEIVED - Step 1</span>
                        <span class="scenario-badge">DNR 1</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a805fa1a2cc195865874d" class="scenario-item external-link" data-keywords="delivered not received step 2" target="_blank">
                        <span class="scenario-text">DELIVERED NOT RECEIVED - Step 2</span>
                        <span class="scenario-badge">DNR 2</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80768dc7f6152ffaa243" class="scenario-item external-link" data-keywords="delivered not received step 3 escalation" target="_blank">
                        <span class="scenario-text">DELIVERED NOT RECEIVED - Step 3: Escalation/Free Replacement</span>
                        <span class="scenario-badge">DNR 3</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80b4b492ff314c99f8c1" class="scenario-item external-link" data-keywords="lost package check tracking supplier update step 1" target="_blank">
                        <span class="scenario-text">LOST PACKAGE - Step 1: Check tracking - Ask supplier for update</span>
                        <span class="scenario-badge">LOST 1</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80dbb82bc8cccb659592" class="scenario-item external-link" data-keywords="lost package replacement after supplier confirmation step 2" target="_blank">
                        <span class="scenario-text">LOST PACKAGE - Step 2A: Offer replacement (after supplier confirmation)</span>
                        <span class="scenario-badge">LOST 2A</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80c88d7de4c834ae3f07" class="scenario-item external-link" data-keywords="lost package replacement policy step 2" target="_blank">
                        <span class="scenario-text">LOST PACKAGE - Step 2B: Offer replacement policy</span>
                        <span class="scenario-badge">LOST 2B</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80c48a1ad342096dfe03" class="scenario-item external-link" data-keywords="lost package refund step 2" target="_blank">
                        <span class="scenario-text">LOST PACKAGE - Step 2C: Offer refund (lost package)</span>
                        <span class="scenario-badge">LOST 2C</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80419a05edef9c0b1380" class="scenario-item external-link" data-keywords="send new package customer accept replacement" target="_blank">
                        <span class="scenario-text">Send new package (customer accepts replacement)</span>
                        <span class="scenario-badge">SHIP</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a8010ab9bc5b6b2734307" class="scenario-item external-link" data-keywords="send new package with tracking information carrier supplier" target="_blank">
                        <span class="scenario-text">Send new package - With tracking info</span>
                        <span class="scenario-badge">TRACK</span>
                        <span class="link-icon">🔗</span>
                    </a>
                </div>
            </div>
            
            <div class="category" data-category="rtc">
                <div class="category-header">🇨🇳 5. RETURN TO CHINA (RTC)</div>
                <div class="scenario-list">
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a808fbd92dd4ce3aebf59" class="scenario-item external-link" data-keywords="rtc stuck in customs 20 days tracking parcel aftership" target="_blank">
                        <span class="scenario-text">RTC - Stuck in customs >20 days</span>
                        <span class="scenario-badge">CUSTOMS</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a802faa51fab346124e45" class="scenario-item external-link" data-keywords="rtc cleared no movement tracking parcel aftership" target="_blank">
                        <span class="scenario-text">RTC - Cleared but no movement</span>
                        <span class="scenario-badge">CLEARED</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a801489d1fd3ebabdbbf9" class="scenario-item external-link" data-keywords="rtc sent back 20% 50% tracking parcel aftership" target="_blank">
                        <span class="scenario-text">RTC - Sent back (20% to 50% refund)</span>
                        <span class="scenario-badge">REFUND</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a80b2a96be06c92230003" class="scenario-item external-link" data-keywords="rtc missing invoice rts tracking parcel aftership" target="_blank">
                        <span class="scenario-text">RTC - Missing invoice/Return to sender</span>
                        <span class="scenario-badge">INVOICE</span>
                        <span class="link-icon">🔗</span>
                    </a>
                </div>
            </div>
            
            <div class="category" data-category="general">
                <div class="category-header">⚙️ 6. GENERAL</div>
                <div class="scenario-list">
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a808880a1dd78a68c61ad" class="scenario-item external-link" data-keywords="unsubscribe newsletter" target="_blank">
                        <span class="scenario-text">Unsubscribe from newsletter</span>
                        <span class="scenario-badge">UNSUB</span>
                        <span class="link-icon">🔗</span>
                    </a>
                    <a href="https://www.notion.so/Customer-Support-Management-SOP-2241d115f40a806ca5c3dea7e10beec5?source=copy_link#2241d115f40a801d9409c1e4f95753a5" class="scenario-item external-link" data-keywords="general we're checking pending questions" target="_blank">
                        <span class="scenario-text">General - We're checking (Pending questions)</span>
                        <span class="scenario-badge">PENDING</span>
                        <span class="link-icon">🔗</span>
                    </a>
                </div>
            </div>
        </div>
        
        <div class="no-results hidden" id="noResults">
            <h3>🔍 No results found</h3>
            <p>Try different keywords or check the spelling</p>
        </div>
        
        <div class="stats">
            <div class="stat-item">
                <span>📊</span>
                <span><strong id="totalScenarios">0</strong> total scenarios</span>
            </div>
            <div class="stat-item">
                <span>⚡</span>
                <span>Quick search enabled</span>
            </div>
            <div class="stat-item">
                <span>🎯</span>
                <span>Instant template access</span>
            </div>
        </div>
    </div>

    <script>
        // Count total scenarios
        const totalScenarios = document.querySelectorAll('.scenario-item').length;
        document.getElementById('totalScenarios').textContent = totalScenarios;
        
        // Search functionality
        const searchInput = document.getElementById('searchInput');
        const categoriesContainer = document.getElementById('categoriesContainer');
        const noResults = document.getElementById('noResults');
        
        searchInput.addEventListener('input', function() {
            const searchTerm = this.value.toLowerCase().trim();
            
            if (searchTerm === '') {
                // Show all categories and scenarios
                document.querySelectorAll('.category').forEach(category => {
                    category.classList.remove('hidden');
                    category.querySelectorAll('.scenario-item').forEach(item => {
                        item.classList.remove('hidden');
                    });
                });
                noResults.classList.add('hidden');
                categoriesContainer.classList.remove('hidden');
                return;
            }
            
            let hasResults = false;
            
            document.querySelectorAll('.category').forEach(category => {
                let categoryHasResults = false;
                
                category.querySelectorAll('.scenario-item').forEach(item => {
                    const keywords = item.getAttribute('data-keywords');
                    const text = item.textContent.toLowerCase();
                    
                    if (keywords.includes(searchTerm) || text.includes(searchTerm)) {
                        item.classList.remove('hidden');
                        categoryHasResults = true;
                        hasResults = true;
                    } else {
                        item.classList.add('hidden');
                    }
                });
                
                if (categoryHasResults) {
                    category.classList.remove('hidden');
                } else {
                    category.classList.add('hidden');
                }
            });
            
            if (hasResults) {
                noResults.classList.add('hidden');
                categoriesContainer.classList.remove('hidden');
            } else {
                noResults.classList.remove('hidden');
                categoriesContainer.classList.add('hidden');
            }
        });
        
        // Add click functionality to scenario items
        document.querySelectorAll('.scenario-item').forEach(item => {
            item.addEventListener('click', function() {
                // Add a subtle animation
                this.style.transform = 'scale(0.98)';
                setTimeout(() => {
                    this.style.transform = 'scale(1)';
                }, 100);
                
                // Here you could add functionality to copy template or navigate
                console.log('Selected scenario:', this.textContent);
            });
        });
    </script>
</body>
</html>
