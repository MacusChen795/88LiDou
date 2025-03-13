# 88LiDou
<!DOCTYPE html>
<html lang="zh-TW">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="峇里島六日遊行程規劃，包含住宿、餐廳、交通、活動和實用提示 | 2025年3月31日 - 4月5日">
  <meta name="keywords" content="峇里島,旅遊,行程規劃,烏布,水明漾,旅行">
  <title>峇里島六日遊 | 3/31-4/5</title>
  <style>
      :root {
          --primary: #0a9396;
          --secondary: #ee9b00;
          --dark: #001219;
          --light: #f8f9fa;
          --accent: #e76f51;
          --gray: #6c757d;
          --light-bg: #f1f8f9;
      }
      
      * {
          margin: 0;
          padding: 0;
          box-sizing: border-box;
          font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      }
      
      html {
          scroll-behavior: smooth; /* 添加平滑滾動效果 */
          scroll-padding-top: 70px; /* 為固定導航欄添加滾動內邊距 */
      }
      
      body {
          background-color: var(--light);
          color: var(--dark);
          line-height: 1.6;
          overflow-x: hidden; /* 防止水平滾動 */
      }
      
      .container {
          max-width: 1200px;
          margin: 0 auto;
          padding: 0 20px;
          position: relative; /* 確保子元素定位正確 */
      }
      
      header {
          background-color: var(--primary);
          color: white;
          padding: 2rem 0;
          text-align: center;
          background-image: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1537996194471-e657df975ab4?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
          background-size: cover;
          background-position: center;
          position: relative;
      }
      
      header h1 {
          font-size: 2.5rem;
          margin-bottom: 1rem;
      }
      
      header p {
          font-size: 1.2rem;
          max-width: 700px;
          margin: 0 auto;
      }
      
      nav {
          background-color: var(--dark);
          position: sticky;
          top: 0;
          z-index: 1000; /* 確保導航欄在最上層 */
          box-shadow: 0 2px 10px rgba(0,0,0,0.1); /* 添加陰影增強視覺效果 */
      }
      
      nav ul {
          display: flex;
          justify-content: center;
          list-style: none;
          flex-wrap: wrap;
      }
      
      nav ul li a {
          display: block;
          color: white;
          text-decoration: none;
          padding: 1rem 1.5rem;
          transition: all 0.3s ease;
          position: relative; /* 為懸停效果添加定位 */
      }
      
      nav ul li a:hover {
          background-color: var(--primary);
      }
      
      /* 添加活動指示器 */
      nav ul li a:after {
          content: '';
          position: absolute;
          bottom: 0;
          left: 50%;
          width: 0;
          height: 3px;
          background-color: var(--secondary);
          transition: all 0.3s ease;
          transform: translateX(-50%);
      }
      
      nav ul li a:hover:after {
          width: 70%;
      }
      
      section {
          padding: 5rem 0; /* 增加內邊距以提供更多空間 */
          scroll-margin-top: 70px; /* 確保滾動定位正確 */
          position: relative; /* 確保子元素定位正確 */
      }
      
      section h2 {
          text-align: center;
          margin-bottom: 2rem;
          color: var(--primary);
          position: relative;
          padding-bottom: 0.5rem;
      }
      
      section h2::after {
          content: '';
          position: absolute;
          bottom: 0;
          left: 50%;
          transform: translateX(-50%);
          width: 100px;
          height: 3px;
          background-color: var(--secondary);
      }
      
      .accommodation {
          display: flex;
          flex-wrap: wrap;
          gap: 2rem;
          justify-content: center;
      }
      
      .hotel-card {
          background-color: white;
          border-radius: 8px;
          overflow: hidden;
          box-shadow: 0 4px 12px rgba(0,0,0,0.1);
          flex: 1;
          min-width: 300px;
          max-width: 500px;
          transition: transform 0.3s ease, box-shadow 0.3s ease;
      }
      
      .hotel-card:hover {
          transform: translateY(-5px);
          box-shadow: 0 8px 24px rgba(0,0,0,0.15);
      }
      
      .hotel-image {
          height: 200px;
          background-size: cover;
          background-position: center;
          transition: all 0.5s ease;
      }
      
      .hotel-card:hover .hotel-image {
          transform: scale(1.05);
      }
      
      .hotel-info {
          padding: 1.5rem;
      }
      
      .hotel-info h3 {
          color: var(--primary);
          margin-bottom: 0.5rem;
      }
      
      .advantages, .avoid {
          margin-top: 1rem;
      }
      
      .advantages h4, .avoid h4 {
          margin-bottom: 0.5rem;
          display: flex;
          align-items: center;
      }
      
      .advantages h4::before {
          content: '✓';
          color: green;
          margin-right: 0.5rem;
      }
      
      .avoid h4::before {
          content: '!';
          color: var(--accent);
          margin-right: 0.5rem;
      }
      
      .advantages ul, .avoid ul {
          padding-left: 1.5rem;
      }
      
      .itinerary-days {
          margin-top: 2rem;
      }
      
      .day-card {
          background-color: white;
          border-radius: 8px;
          overflow: hidden;
          box-shadow: 0 4px 12px rgba(0,0,0,0.1);
          margin-bottom: 2rem;
          transition: transform 0.3s ease;
      }
      
      .day-card:hover {
          transform: translateY(-3px);
          box-shadow: 0 6px 18px rgba(0,0,0,0.12);
      }
      
      .day-header {
          background-color: var(--primary);
          color: white;
          padding: 1rem 1.5rem;
          display: flex;
          justify-content: space-between;
          align-items: center;
      }
      
      .day-content {
          padding: 1.5rem;
      }
      
      .timeline {
          position: relative;
          padding-left: 2rem;
      }
      
      .timeline::before {
          content: '';
          position: absolute;
          top: 0;
          bottom: 0;
          left: 8px;
          width: 2px;
          background-color: var(--primary);
      }
      
      .timeline-item {
          position: relative;
          margin-bottom: 1.5rem;
          transition: transform 0.3s ease;
      }
      
      .timeline-item:hover {
          transform: translateX(5px);
      }
      
      .timeline-item:last-child {
          margin-bottom: 0;
      }
      
      .timeline-item::before {
          content: '';
          position: absolute;
          left: -2rem;
          top: 4px;
          width: 16px;
          height: 16px;
          border-radius: 50%;
          background-color: var(--secondary);
          transition: all 0.3s ease;
      }
      
      .timeline-item:hover::before {
          transform: scale(1.2);
          background-color: var(--accent);
      }
      
      .timeline-time {
          font-weight: bold;
          color: var(--primary);
          margin-bottom: 0.25rem;
      }
      
      .timeline-title {
          font-weight: bold;
          margin-bottom: 0.25rem;
      }
      
      .timeline-desc {
          color: var(--gray);
      }
      
      .optimization {
          background-color: var(--light-bg);
          padding: 0.75rem;
          border-left: 3px solid var(--secondary);
          margin-top: 0.5rem;
          transition: all 0.3s ease;
      }
      
      .timeline-item:hover .optimization {
          border-left-color: var(--accent);
          background-color: rgba(231, 111, 81, 0.05);
      }
      
      .optimization strong {
          color: var(--accent);
      }
      
      .restaurant-list, .transport-list, .activity-list, .shopping-list {
          display: grid;
          grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
          gap: 1.5rem;
          margin-top: 2rem;
      }
      
      .list-card {
          background-color: white;
          border-radius: 8px;
          overflow: hidden;
          box-shadow: 0 4px 12px rgba(0,0,0,0.1);
          transition: transform 0.3s ease, box-shadow 0.3s ease;
      }
      
      .list-card:hover {
          transform: translateY(-3px);
          box-shadow: 0 8px 24px rgba(0,0,0,0.15);
      }
      
      .list-header {
          padding: 1rem;
          background-color: var(--primary);
          color: white;
      }
      
      .list-content {
          padding: 1rem;
      }
      
      .list-content p {
          margin-bottom: 0.5rem;
      }
      
      .list-content h4 {
          margin-top: 1rem;
          color: var(--primary);
          border-bottom: 1px solid var(--light-bg);
          padding-bottom: 0.3rem;
      }
      
      .list-content h4:first-child {
          margin-top: 0;
      }
      
      .tips-section {
          background-color: var(--light-bg);
      }
      
      .tips-container {
          display: grid;
          grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
          gap: 1.5rem;
      }
      
      .tip-card {
          background-color: white;
          border-radius: 8px;
          padding: 1.5rem;
          box-shadow: 0 4px 12px rgba(0,0,0,0.1);
          transition: transform 0.3s ease;
      }
      
      .tip-card:hover {
          transform: translateY(-3px);
          box-shadow: 0 8px 24px rgba(0,0,0,0.15);
      }
      
      .tip-card h3 {
          color: var(--primary);
          margin-bottom: 1rem;
          display: flex;
          align-items: center;
          border-bottom: 2px solid var(--light-bg);
          padding-bottom: 0.5rem;
      }
      
      .tip-card h3 svg {
          margin-right: 0.5rem;
      }
      
      .tip-card ul {
          padding-left: 1.5rem;
      }
      
      .tip-card li {
          margin-bottom: 0.5rem;
      }
      
      footer {
          background-color: var(--dark);
          color: white;
          text-align: center;
          padding: 2rem 0;
          margin-top: 3rem;
      }
      
      /* 返回頂部按鈕 */
      .back-to-top {
          position: fixed;
          bottom: 30px;
          right: 30px;
          background-color: var(--primary);
          color: white;
          width: 50px;
          height: 50px;
          border-radius: 50%;
          display: flex;
          justify-content: center;
          align-items: center;
          text-decoration: none;
          opacity: 0;
          transition: all 0.3s ease;
          z-index: 999;
          box-shadow: 0 2px 10px rgba(0,0,0,0.2);
      }
      
      .back-to-top.visible {
          opacity: 1;
      }
      
      .back-to-top:hover {
          background-color: var(--secondary);
          transform: translateY(-3px);
      }
      
      /* 載入動畫 */
      .page-loader {
          position: fixed;
          top: 0;
          left: 0;
          width: 100%;
          height: 100%;
          background-color: var(--light);
          display: flex;
          justify-content: center;
          align-items: center;
          z-index: 9999;
          transition: opacity 0.5s ease;
      }
      
      .loader {
          width: 50px;
          height: 50px;
          border: 5px solid var(--light-bg);
          border-top: 5px solid var(--primary);
          border-radius: 50%;
          animation: spin 1s linear infinite;
      }
      
      @keyframes spin {
          0% { transform: rotate(0deg); }
          100% { transform: rotate(360deg); }
      }
      
      /* 活動導航指示器 */
      .active-section-indicator {
          position: fixed;
          top: 70px;
          right: 20px;
          background-color: var(--primary);
          color: white;
          padding: 0.5rem 1rem;
          border-radius: 20px;
          font-size: 0.9rem;
          opacity: 0;
          transform: translateX(50px);
          transition: all 0.3s ease;
          z-index: 998;
      }
      
      .active-section-indicator.visible {
          opacity: 1;
          transform: translateX(0);
      }
      
      /* 響應式設計優化 */
      @media (max-width: 768px) {
          header h1 {
              font-size: 2rem;
          }
          
          nav {
              overflow-x: auto; /* 允許在小屏幕上水平滾動導航 */
              -webkit-overflow-scrolling: touch;
          }
          
          nav ul {
              width: max-content;
              padding: 0 10px;
          }
          
          nav ul li a {
              padding: 0.75rem 1rem;
              white-space: nowrap;
          }
          
          .hotel-card, .day-card {
              min-width: 100%;
          }
          
          .restaurant-list, .transport-list, .activity-list, .shopping-list {
              grid-template-columns: 1fr;
          }
          
          .back-to-top {
              bottom: 20px;
              right: 20px;
              width: 40px;
              height: 40px;
          }
          
          section {
              padding: 3rem 0;
          }
      }
      
      /* 打印樣式 */
      @media print {
          nav, .back-to-top {
              display: none;
          }
          
          body {
              font-size: 12pt;
              line-height: 1.5;
          }
          
          section {
              page-break-inside: avoid;
              padding: 1rem 0;
          }
          
          .hotel-card, .day-card, .list-card, .tip-card {
              break-inside: avoid;
              box-shadow: none;
              border: 1px solid #ddd;
          }
          
          header {
              background-image: none !important;
              background-color: white;
              color: black;
              padding: 1rem 0;
          }
      }
  </style>
</head>
<body>
  <!-- 頁面載入動畫 -->
  <div class="page-loader">
      <div class="loader"></div>
  </div>

  <header>
      <div class="container">
          <h1>峇里島六日遊精選行程</h1>
          <p>2025年3月31日 - 4月5日</p>
      </div>
  </header>
  
  <nav id="main-nav">
      <ul>
          <li><a href="#accommodation" class="nav-link">住宿選擇</a></li>
          <li><a href="#itinerary" class="nav-link">詳細行程</a></li>
          <li><a href="#restaurants" class="nav-link">餐廳精選</a></li>
          <li><a href="#transport" class="nav-link">交通安排</a></li>
          <li><a href="#activities" class="nav-link">活動預訂</a></li>
          <li><a href="#shopping" class="nav-link">購物指南</a></li>
          <li><a href="#tips" class="nav-link">實用提示</a></li>
      </ul>
  </nav>
  
  <!-- 活動區域指示器 -->
  <div class="active-section-indicator" id="section-indicator">當前區域</div>
  
  <section id="accommodation">
      <div class="container">
          <h2>住宿選擇</h2>
          <div class="accommodation">
              <div class="hotel-card">
                  <div class="hotel-image" style="background-image: url('https://images.unsplash.com/photo-1566073771259-6a8506099945?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');" loading="lazy"></div>
                  <div class="hotel-info">
                      <h3>烏布地區 (Day 1-3)</h3>
                      <p><strong>推薦: Maya Ubud Resort & Spa</strong></p>
                      <div class="advantages">
                          <h4>優勢</h4>
                          <ul>
                              <li>性價比高、環境優美</li>
                              <li>河谷SPA體驗極佳</li>
                              <li>提供接駁車服務</li>
                          </ul>
                      </div>
                      <div class="avoid">
                          <h4>避開問題</h4>
                          <ul>
                              <li>選擇新裝修的房型（預訂時特別註明）</li>
                              <li>提前查詢並記錄接駁車時間表</li>
                              <li>早餐在酒店享用，晚餐可選擇外出體驗當地餐廳</li>
                          </ul>
                      </div>
                  </div>
              </div>
              
              <div class="hotel-card">
                  <div class="hotel-image" style="background-image: url('https://images.unsplash.com/photo-1540541338287-41700207dee6?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');" loading="lazy"></div>
                  <div class="hotel-info">
                      <h3>南部海灘區 (Day 4-6)</h3>
                      <p><strong>推薦: Alila Seminyak</strong></p>
                      <div class="advantages">
                          <h4>優勢</h4>
                          <ul>
                              <li>現代設計、多個泳池選擇</li>
                              <li>直接面對海灘</li>
                              <li>位置便利</li>
                          </ul>
                      </div>
                      <div class="avoid">
                          <h4>避開問題</h4>
                          <ul>
                              <li>選擇高樓層海景房，避免噪音問題</li>
                              <li>提前預訂酒店內SPA和餐廳</li>
                              <li>避開週末入住，減少公共區域擁擠問題</li>
                          </ul>
                      </div>
                  </div>
              </div>
          </div>
      </div>
  </section>
  
  <section id="itinerary">
      <div class="container">
          <h2>詳細行程</h2>
          <div class="itinerary-days">
              <div class="day-card">
                  <div class="day-header">
                      <h3>第1天 (3/31)</h3>
                      <span>抵達與烏布文化</span>
                  </div>
                  <div class="day-content">
                      <div class="timeline">
                          <div class="timeline-item">
                              <div class="timeline-time">早上/中午</div>
                              <div class="timeline-title">抵達峇里島登巴薩機場</div>
                              <div class="timeline-desc">
                                  <p><strong>交通安排</strong>：提前預訂私人接機服務直達Maya Ubud (約1.5小時)</p>
                              </div>
                          </div>
                          
                          <div class="timeline-item">
                              <div class="timeline-time">下午</div>
                              <div class="timeline-title">辦理入住、熟悉酒店環境、享受下午茶</div>
                              <div class="optimization">
                                  <strong>優化</strong>：充分利用酒店設施，緩解旅途疲勞
                              </div>
                          </div>
                          
                          <div class="timeline-item">
                              <div class="timeline-time">傍晚 (17:00-19:00)</div>
                              <div class="timeline-title">參觀烏布皇宮和烏布傳統市場</div>
                              <div class="optimization">
                                  <strong>優化</strong>：選擇傍晚時段，避開白天的人潮和炎熱
                              </div>
                          </div>
                          
                          <div class="timeline-item">
                              <div class="timeline-time">晚餐</div>
                              <div class="timeline-title">在 Locavore To Go (Locavore的平價分店) 享用晚餐</div>
                              <div class="optimization">
                                  <strong>優化</strong>：品質穩定、價格合理，避開主店需提前數月預約的問題
                              </div>
                          </div>
                      </div>
                  </div>
              </div>
              
              <div class="day-card">
                  <div class="day-header">
                      <h3>第2天 (4/1)</h3>
                      <span>瑜珈與SPA</span>
                  </div>
                  <div class="day-content">
                      <div class="timeline">
                          <div class="timeline-item">
                              <div class="timeline-time">早晨 (7:00)</div>
                              <div class="timeline-title">Maya Ubud酒店內瑜珈課程</div>
                              <div class="optimization">
                                  <strong>優化</strong>：避免往返Yoga Barn的交通時間，享受更私密的體驗
                              </div>
                          </div>
                          
                          <div class="timeline-item">
                              <div class="timeline-time">早餐後 (9:00)</div>
                              <div class="timeline-title">參觀德格拉朗梯田 (Tegallalang)</div>
                              <div class="optimization">
                                  <strong>優化</strong>：上午參觀，光線最佳且遊客較少
                              </div>
                          </div>
                          
                          <div class="timeline-item">
                              <div class="timeline-time">午餐 (12:00)</div>
                              <div class="timeline-title">在梯田附近的Bebek Bengil Ubud分店享用髒鴨餐</div>
                              <div class="optimization">
                                  <strong>優化</strong>：選擇午餐時段，食材更新鮮
                              </div>
                          </div>
                          
                          <div class="timeline-item">
                              <div class="timeline-time">下午 (14:00-17:00)</div>
                              <div class="timeline-title">返回Maya Ubud享受河谷SPA體驗</div>
                              <div class="optimization">
                                  <strong>優化</strong>：利用酒店著名的河谷SPA設施，避免往返外部SPA的交通
                              </div>
                          </div>
                          
                          <div class="timeline-item">
                              <div class="timeline-time">晚餐</div>
                              <div class="timeline-title">在酒店內餐廳或使用接駁車前往Hujan Locale餐廳</div>
                              <div class="optimization">
                                  <strong>優化</strong>：Hujan Locale提供創新峇里菜，評價穩定且價格合理
                              </div>
                          </div>
                      </div>
                  </div>
              </div>
              
              <div class="day-card">
                  <div class="day-header">
                      <h3>第3天 (4/2)</h3>
                      <span>烹飪課程與文化體驗</span>
                  </div>
                  <div class="day-content">
                      <div class="timeline">
                          <div class="timeline-item">
                              <div class="timeline-time">早晨 (7:30)</div>
                              <div class="timeline-title">提前到達聖泉寺 (Tirta Empul)</div>
                              <div class="optimization">
                                  <strong>優化</strong>：早上參觀避開團隊遊客，體驗更加寧靜
                              </div>
                          </div>
                          
                          <div class="timeline-item">
                              <div class="timeline-time">上午至中午 (10:00-14:00)</div>
                              <div class="timeline-title">參加Paon Bali烹飪課程</div>
                              <div class="optimization">
                                  <strong>優化</strong>：提前預訂小團體課程，確保個人化體驗
                              </div>
                          </div>
                          
                          <div class="timeline-item">
                              <div class="timeline-time">下午 (15:00)</div>
                              <div class="timeline-title">參觀聖猴森林公園</div>
                              <div class="optimization">
                                  <strong>優化</strong>：下午3點後參觀，避開中午人潮和炎熱
                              </div>
                          </div>
                          
                          <div class="timeline-item">
                              <div class="timeline-time">傍晚 (18:30)</div>
                              <div class="timeline-title">在Lotus Cafe欣賞傳統巴厘舞表演並享用晚餐</div>
                              <div class="optimization">
                                  <strong>優化</strong>：提前預訂靠近舞台的座位
                              </div>
                          </div>
                      </div>
                  </div>
              </div>
              
              <div class="day-card">
                  <div class="day-header">
                      <h3>第4天 (4/3)</h3>
                      <span>前往南部海灘區</span>
                  </div>
                  <div class="day-content">
                      <div class="timeline">
                          <div class="timeline-item">
                              <div class="timeline-time">早上 (8:00)</div>
                              <div class="timeline-title">從烏布出發前往水明漾</div>
                              <div class="optimization">
                                <strong>優化</strong>：早上出發避開中午交通高峰
                            </div>
                        </div>
                        
                        <div class="timeline-item">
                            <div class="timeline-time">中午 (11:00)</div>
                            <div class="timeline-title">抵達Alila Seminyak辦理入住</div>
                            <div class="optimization">
                                <strong>優化</strong>：提前聯繫酒店安排早check-in
                            </div>
                        </div>
                        
                        <div class="timeline-item">
                            <div class="timeline-time">午餐 (12:30)</div>
                            <div class="timeline-title">在酒店海灘餐廳輕鬆用餐</div>
                        </div>
                        
                        <div class="timeline-item">
                            <div class="timeline-time">下午 (15:00-17:30)</div>
                            <div class="timeline-title">前往烏魯瓦圖廟</div>
                            <div class="optimization">
                                <strong>優化</strong>：下午參觀，光線適合拍照且可順便觀看夕陽
                            </div>
                        </div>
                        
                        <div class="timeline-item">
                            <div class="timeline-time">傍晚 (18:00)</div>
                            <div class="timeline-title">欣賞Kecak火舞表演</div>
                            <div class="optimization">
                                <strong>優化</strong>：提前預訂前排座位
                            </div>
                        </div>
                        
                        <div class="timeline-item">
                            <div class="timeline-time">晚餐 (20:00)</div>
                            <div class="timeline-title">在Jimbaran海灘的Menega Cafe享用海鮮燒烤</div>
                            <div class="optimization">
                                <strong>優化</strong>：預訂靠海的座位，提前點餐避免等待
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="day-card">
                <div class="day-header">
                    <h3>第5天 (4/4)</h3>
                    <span>冒險與美食</span>
                </div>
                <div class="day-content">
                    <div class="timeline">
                        <div class="timeline-item">
                            <div class="timeline-time">早上 (8:00-11:00)</div>
                            <div class="timeline-title">ATV越野車探險</div>
                            <div class="optimization">
                                <strong>優化</strong>：選擇早上時段，避開炎熱和下午可能的雷陣雨
                            </div>
                        </div>
                        
                        <div class="timeline-item">
                            <div class="timeline-time">午餐 (12:30)</div>
                            <div class="timeline-title">在Merah Putih餐廳享用現代印尼料理</div>
                            <div class="optimization">
                                <strong>優化</strong>：替代評價下滑的Bebek Bengil，體驗更高品質的創新料理
                            </div>
                        </div>
                        
                        <div class="timeline-item">
                            <div class="timeline-time">下午 (14:30-17:00)</div>
                            <div class="timeline-title">在Alila Seminyak泳池放鬆或享受SPA</div>
                            <div class="optimization">
                                <strong>優化</strong>：避免中午陽光強烈時段的戶外活動
                            </div>
                        </div>
                        
                        <div class="timeline-item">
                            <div class="timeline-time">傍晚 (17:30)</div>
                            <div class="timeline-title">在酒店海灘欣賞日落</div>
                        </div>
                        
                        <div class="timeline-item">
                            <div class="timeline-time">晚餐 (19:30)</div>
                            <div class="timeline-title">在Sarong餐廳享用晚餐</div>
                            <div class="optimization">
                                <strong>優化</strong>：替代需要提前很久預約的La Lucciola，Sarong提供類似的優質體驗
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="day-card">
                <div class="day-header">
                    <h3>第6天 (4/5)</h3>
                    <span>最後享受與離開</span>
                </div>
                <div class="day-content">
                    <div class="timeline">
                        <div class="timeline-item">
                            <div class="timeline-time">早上 (7:00-9:00)</div>
                            <div class="timeline-title">在海灘散步或最後的游泳時光</div>
                            <div class="optimization">
                                <strong>優化</strong>：早晨的海灘最為寧靜美麗
                            </div>
                        </div>
                        
                        <div class="timeline-item">
                            <div class="timeline-time">上午 (10:00-12:00)</div>
                            <div class="timeline-title">在水明漾精品店購物</div>
                            <div class="optimization">
                                <strong>優化</strong>：選擇小型精品店而非大型連鎖伴手禮店
                            </div>
                        </div>
                        
                        <div class="timeline-item">
                            <div class="timeline-time">午餐 (12:30)</div>
                            <div class="timeline-title">在Revolver Coffee或Sisterfields享用輕食午餐</div>
                            <div class="optimization">
                                <strong>優化</strong>：這些咖啡廳提供優質餐點，是當地居民和長期旅客的最愛
                            </div>
                        </div>
                        
                        <div class="timeline-item">
                            <div class="timeline-time">下午</div>
                            <div class="timeline-title">整理行李，前往機場</div>
                            <div class="timeline-desc">
                                <p><strong>交通安排</strong>：提前3小時到達機場，避開可能的交通擁堵</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<section id="restaurants">
    <div class="container">
        <h2>餐廳精選與預訂建議</h2>
        <div class="restaurant-list">
            <div class="list-card">
                <div class="list-header">
                    <h3>烏布地區</h3>
                </div>
                <div class="list-content">
                    <h4>Hujan Locale</h4>
                    <p><strong>特色</strong>：創新印尼菜，由知名主廚Will Meyrick創立</p>
                    <p><strong>預訂</strong>：建議提前3-5天預訂</p>
                    <p><strong>價格</strong>：中高檔，每人約NT$800-1,200</p>
                    
                    <h4>Locavore To Go</h4>
                    <p><strong>特色</strong>：米其林指南推薦Locavore的平價分店</p>
                    <p><strong>預訂</strong>：不需預訂，但建議避開用餐高峰</p>
                    <p><strong>價格</strong>：中檔，每人約NT$500-800</p>
                    
                    <h4>Lotus Cafe</h4>
                    <p><strong>特色</strong>：面對蓮花池，可欣賞傳統巴厘舞表演</p>
                    <p><strong>預訂</strong>：舞蹈表演晚餐需提前1-2天預訂</p>
                    <p><strong>價格</strong>：中檔，每人約NT$600-900</p>
                </div>
            </div>
            
            <div class="list-card">
                <div class="list-header">
                    <h3>水明漾/金巴蘭地區</h3>
                </div>
                <div class="list-content">
                    <h4>Menega Cafe (金巴蘭)</h4>
                    <p><strong>特色</strong>：海灘燒烤海鮮，當地人推薦</p>
                    <p><strong>預訂</strong>：建議提前1天預訂靠海位置</p>
                    <p><strong>價格</strong>：中高檔，每人約NT$900-1,500</p>
                    
                    <h4>Sarong</h4>
                    <p><strong>特色</strong>：精緻東南亞料理，優雅氛圍</p>
                    <p><strong>預訂</strong>：建議提前1週預訂</p>
                    <p><strong>價格</strong>：高檔，每人約NT$1,500-2,500</p>
                    
                    <h4>Merah Putih</h4>
                    <p><strong>特色</strong>：現代印尼料理，建築設計獨特</p>
                    <p><strong>預訂</strong>：建議提前3-5天預訂</p>
                    <p><strong>價格</strong>：中高檔，每人約NT$1,000-1,800</p>
                </div>
            </div>
            
            <div class="list-card">
                <div class="list-header">
                    <h3>咖啡廳與輕食</h3>
                </div>
                <div class="list-content">
                    <h4>Revolver Coffee</h4>
                    <p><strong>特色</strong>：澳洲風格咖啡館，早午餐選擇豐富</p>
                    <p><strong>預訂</strong>：不需預訂，但週末可能需要等位</p>
                    <p><strong>價格</strong>：中檔，每人約NT$400-700</p>
                    
                    <h4>Sisterfields</h4>
                    <p><strong>特色</strong>：時尚咖啡廳，健康料理選擇多</p>
                    <p><strong>預訂</strong>：不需預訂，但建議避開用餐高峰</p>
                    <p><strong>價格</strong>：中檔，每人約NT$500-800</p>
                    
                    <h4>Clear Cafe (烏布)</h4>
                    <p><strong>特色</strong>：有機健康餐點，環境優美</p>
                    <p><strong>預訂</strong>：不需預訂</p>
                    <p><strong>價格</strong>：中檔，每人約NT$400-700</p>
                </div>
            </div>
        </div>
    </div>
</section>

<section id="transport">
    <div class="container">
        <h2>交通安排與建議</h2>
        <div class="transport-list">
            <div class="list-card">
                <div class="list-header">
                    <h3>機場接送</h3>
                </div>
                <div class="list-content">
                    <p><strong>推薦方式</strong>：提前預訂私人接送服務</p>
                    <p><strong>預估費用</strong>：機場至烏布約NT$800-1,000；機場至水明漾約NT$600-800</p>
                    <p><strong>預訂平台</strong>：Klook、GetYourGuide或直接透過酒店安排</p>
                    <p><strong>注意事項</strong>：</p>
                    <ul>
                        <li>提供航班資訊和抵達時間</li>
                        <li>確認是否包含通行費和停車費</li>
                        <li>預留司機聯繫方式以便抵達後聯繫</li>
                    </ul>
                </div>
            </div>
            
            <div class="list-card">
                <div class="list-header">
                    <h3>日常交通</h3>
                </div>
                <div class="list-content">
                    <h4>包車服務</h4>
                    <p><strong>推薦情境</strong>：全天行程或多景點遊覽</p>
                    <p><strong>預估費用</strong>：全天8-10小時約NT$2,000-2,500</p>
                    <p><strong>預訂方式</strong>：提前1-2天透過酒店或線上平台預訂</p>
                    
                    <h4>Grab/Gojek (叫車App)</h4>
                    <p><strong>推薦情境</strong>：短途移動，尤其在水明漾區域</p>
                    <p><strong>預估費用</strong>：視距離而定，短途約NT$100-300</p>
                    <p><strong>使用提示</strong>：部分地區可能有限制，建議在人潮較多處叫車</p>
                    
                    <h4>酒店接駁車</h4>
                    <p><strong>推薦情境</strong>：往返酒店與附近熱門地點</p>
                    <p><strong>費用</strong>：多為免費或象徵性收費</p>
                    <p><strong>注意事項</strong>：查詢時間表並提前預約座位</p>
                </div>
            </div>
            
            <div class="list-card">
                <div class="list-header">
                    <h3>交通優化建議</h3>
                </div>
                <div class="list-content">
                    <ul>
                        <li><strong>避開交通高峰</strong>：上午9-10點和下午4-6點交通最為擁堵</li>
                        <li><strong>合理規劃路線</strong>：同區域景點安排在同一天參觀</li>
                        <li><strong>預留緩衝時間</strong>：峇里島交通狀況不穩定，行程間預留足夠緩衝</li>
                        <li><strong>雨季注意事項</strong>：3-4月為雨季尾聲，部分山區道路可能狀況不佳</li>
                        <li><strong>下載離線地圖</strong>：Google Maps離線地圖功能非常有用</li>
                        <li><strong>準備小額現金</strong>：部分通行費和小費需使用現金支付</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</section>

<section id="activities">
    <div class="container">
        <h2>活動預訂與體驗</h2>
        <div class="activity-list">
            <div class="list-card">
                <div class="list-header">
                    <h3>文化體驗</h3>
                </div>
                <div class="list-content">
                    <h4>Kecak火舞表演 (烏魯瓦圖)</h4>
                    <p><strong>預訂平台</strong>：Klook、GetYourGuide或現場購票</p>
                    <p><strong>費用</strong>：約NT$400-600/人</p>
                    <p><strong>建議</strong>：提前30分鐘到達選擇最佳座位</p>
                    
                    <h4>Paon Bali烹飪課程</h4>
                    <p><strong>預訂平台</strong>：官網或Airbnb體驗</p>
                    <p><strong>費用</strong>：約NT$1,200-1,500/人</p>
                    <p><strong>建議</strong>：選擇包含市場採購的完整課程</p>
                    
                    <h4>傳統巴厘舞表演</h4>
                    <p><strong>地點</strong>：Lotus Cafe或烏布皇宮</p>
                    <p><strong>費用</strong>：約NT$300-500/人</p>
                    <p><strong>建議</strong>：結合晚餐體驗更為便利</p>
                </div>
            </div>
            
            <div class="list-card">
                <div class="list-header">
                    <h3>戶外活動</h3>
                </div>
                <div class="list-content">
                    <h4>ATV越野車探險</h4>
                    <p><strong>預訂平台</strong>：Klook、GetYourGuide</p>
                    <p><strong>費用</strong>：約NT$1,500-2,000/人</p>
                    <p><strong>建議</strong>：選擇包含接送的套餐，穿著可髒的衣物</p>
                    
                    <h4>河谷SPA體驗</h4>
                    <p><strong>地點</strong>：Maya Ubud Resort</p>
                    <p><strong>費用</strong>：約NT$3,000-5,000/人</p>
                    <p><strong>建議</strong>：選擇2小時以上的套餐，充分享受環境</p>
                    
                    <h4>瑜珈課程</h4>
                    <p><strong>地點</strong>：酒店內或Yoga Barn (烏布)</p>
                    <p><strong>費用</strong>：約NT$500-800/堂</p>
                    <p><strong>建議</strong>：初學者選擇溫和流派，提前15分鐘到達</p>
                </div>
            </div>
            
            <div class="list-card">
                <div class="list-header">
                    <h3>景點參觀</h3>
                </div>
                <div class="list-content">
                    <h4>德格拉朗梯田</h4>
                    <p><strong>門票</strong>：免費，但各觀景台可能收取小額費用</p>
                    <p><strong>建議時間</strong>：上午9-11點，光線最佳</p>
                    <p><strong>注意事項</strong>：準備小額現金支付觀景台費用</p>
                    
                    <h4>聖泉寺 (Tirta Empul)</h4>
                    <p><strong>門票</strong>：約NT$300/人</p>
                    <p><strong>建議時間</strong>：早上開門後立即前往</p>
                    <p><strong>注意事項</strong>：需著紗籠入內，可現場租借</p>
                    
                    <h4>烏魯瓦圖廟</h4>
                    <p><strong>門票</strong>：約NT$350/人</p>
                    <p><strong>建議時間</strong>：下午4-6點，可順便欣賞日落</p>
                    <p><strong>注意事項</strong>：防範猴子搶奪物品，不要攜帶貴重飾品</p>
                </div>
            </div>
        </div>
    </div>
</section>

<section id="shopping">
    <div class="container">
        <h2>購物指南</h2>
        <div class="shopping-list">
            <div class="list-card">
                <div class="list-header">
                    <h3>烏布購物區</h3>
                </div>
                <div class="list-content">
                    <h4>烏布傳統市場</h4>
                    <p><strong>特色</strong>：傳統手工藝品、紡織品、木雕</p>
                    <p><strong>建議時間</strong>：傍晚或早上</p>
                    <p><strong>議價技巧</strong>：開價的30-50%是合理價格</p>
                    
                    <h4>Threads of Life</h4>
                    <p><strong>特色</strong>：高品質傳統紡織品，支持當地工匠</p>
                    <p><strong>價格</strong>：中高檔</p>
                    <p><strong>建議</strong>：尋找具有故事性和文化意義的作品</p>
                    
                    <h4>Ubud Main Street精品店</h4>
                    <p><strong>特色</strong>：現代設計與傳統工藝結合的商品</p>
                    <p><strong>價格</strong>：中檔</p>
                    <p><strong>建議</strong>：尋找獨特設計師品牌</p>
                </div>
            </div>
            
            <div class="list-card">
                <div class="list-header">
                    <h3>水明漾購物區</h3>
                </div>
                <div class="list-content">
                    <h4>Seminyak Square</h4>
                    <p><strong>特色</strong>：時尚服飾、泳裝、家居用品</p>
                    <p><strong>價格</strong>：中高檔</p>
                    <p><strong>建議</strong>：尋找本地設計師品牌</p>
                    
                    <h4>Jalan Kayu Aya (Oberoi Street)</h4>
                    <p><strong>特色</strong>：精品店、設計師服飾、飾品</p>
                    <p><strong>價格</strong>：中高檔</p>
                    <p><strong>建議</strong>：注意比較價格，部分店鋪標價偏高</p>
                    
                    <h4>Nyaman Gallery</h4>
                    <p><strong>特色</strong>：當代藝術、設計師珠寶</p>
                    <p><strong>價格</strong>：高檔</p>
                    <p><strong>建議</strong>：尋找具收藏價值的藝術品</p>
                </div>
            </div>
            
            <div class="list-card">
                <div class="list-header">
                    <h3>伴手禮推薦</h3>
                </div>
                <div class="list-content">
                    <h4>咖啡與茶</h4>
                    <p><strong>推薦</strong>：Kopi Luwak (麝香貓咖啡)、峇里島香料茶</p>
                    <p><strong>購買地點</strong>：Seniman Coffee或當地超市</p>
                    <p><strong>注意</strong>：選擇有道德認證的Kopi Luwak</p>
                    
                    <h4>香氛產品</h4>
                    <p><strong>推薦</strong>：精油、香薰、手工皂</p>
                    <p><strong>購買地點</strong>：Utama Spice、Blue Stone Botanicals</p>
                    <p><strong>建議</strong>：選擇使用當地原料的天然產品</p>
                    
                    <h4>手工藝品</h4>
                    <p><strong>推薦</strong>：木雕、銀飾、蠟染布</p>
                    <p><strong>購買地點</strong>：烏布市場、專業工藝村</p>
                    <p><strong>建議</strong>：選擇體積小、易於攜帶的精緻作品</p>
                </div>
            </div>
        </div>
    </div>
</section>

<section id="tips" class="tips-section">
    <div class="container">
        <h2>實用提示</h2>
        <div class="tips-container">
            <div class="tip-card">
                <h3>貨幣與支付</h3>
                <ul>
                    <li>提前兌換少量印尼盾，機場匯率較差</li>
                    <li>大多數酒店、高檔餐廳接受信用卡</li>
                    <li>小額交易準備印尼盾，面額10萬、5萬最實用</li>
                    <li>使用ATM提款選擇銀行內的機器，避免詐騙</li>
                    <li>記得開通信用卡海外交易功能</li>
                </ul>
            </div>
            
            <div class="tip-card">
                <h3>通訊與網路</h3>
                <ul>
                    <li>機場購買當地SIM卡，Telkomsel覆蓋較好</li>
                    <li>酒店WiFi普遍穩定，但山區可能不穩</li>
                    <li>下載離線地圖和翻譯應用</li>
                    <li>保存重要聯繫人和酒店地址的截圖</li>
                    <li>準備便攜式充電器</li>
                </ul>
            </div>
            
            <div class="tip-card">
                <h3>健康與安全</h3>
                <ul>
                    <li>準備防蚊液、防曬霜和腹瀉藥</li>
                    <li>飲用瓶裝水，避免生食和街邊冰品</li>
                    <li>穿著舒適透氣的衣物，準備防雨裝備</li>
                    <li>尊重當地宗教場所，著裝得體</li>
                    <li>購買旅遊保險，記錄重要醫療資訊</li>
                </ul>
            </div>
            
            <div class="tip-card">
                <h3>文化禮儀</h3>
                <ul>
                    <li>進入寺廟需著紗籠，女性生理期避免入內</li>
                    <li>與當地人交流時保持微笑和耐心</li>
                    <li>拍照前徵求同意，特別是對著當地人</li>
                    <li>避免使用左手遞送物品</li>
                    <li>適量給予小費，服務業約10-15%</li>
                </ul>
            </div>
            
            <div class="tip-card">
                <h3>天氣與季節</h3>
                <ul>
                    <li>3-4月為雨季尾聲，準備輕便雨具</li>
                    <li>早晚溫差大，準備一件薄外套</li>
                    <li>山區和海邊溫度差異明顯</li>
                    <li>紫外線強，戶外活動做好防曬</li>
                    <li>雷雨通常在下午，早上安排戶外活動</li>
                </ul>
            </div>
            
            <div class="tip-card">
                <h3>實用APP</h3>
                <ul>
                    <li>Grab/Gojek：叫車和外送</li>
                    <li>Google Maps：離線地圖導航</li>
                    <li>Google Translate：離線翻譯印尼語</li>
                    <li>XE Currency：貨幣換算</li>
                    <li>AccuWeather：精確天氣預報</li>
                </ul>
            </div>
        </div>
    </div>
</section>

<footer>
    <div class="container">
        <p>峇里島六日遊行程規劃 | 2025年3月31日 - 4月5日</p>
        <p>最後更新：2025年3月13日</p>
    </div>
</footer>

<!-- 返回頂部按鈕 -->
<a href="#" class="back-to-top" id="backToTop" aria-label="返回頂部">↑</a>

<script>
    // 頁面載入完成後執行
    document.addEventListener('DOMContentLoaded', function() {
        // 獲取所有導航連結
        const navLinks = document.querySelectorAll('.nav-link');
        // 獲取所有區塊
        const sections = document.querySelectorAll('section');
        // 獲取返回頂部按鈕
        const backToTop = document.getElementById('backToTop');
        // 獲取區域指示器
        const sectionIndicator = document.getElementById('section-indicator');
        // 獲取頁面載入動畫
        const pageLoader = document.querySelector('.page-loader');
        
        // 隱藏頁面載入動畫
        setTimeout(function() {
            pageLoader.style.opacity = '0';
            setTimeout(function() {
                pageLoader.style.display = 'none';
            }, 500);
        }, 800);
        
        // 為每個導航連結添加點擊事件
        navLinks.forEach(link => {
            link.addEventListener('click', function(e) {
                e.preventDefault();
                
                // 獲取目標區塊ID
                const targetId = this.getAttribute('href').substring(1);
                const targetSection = document.getElementById(targetId);
                
                // 如果找到目標區塊，平滑滾動到該位置
                if (targetSection) {
                    const offsetTop = targetSection.offsetTop - 60; // 減去導航欄高度
                    
                    window.scrollTo({
                        top: offsetTop,
                        behavior: 'smooth'
                    });
                    
                    // 更新URL但不重新載入頁面
                    history.pushState(null, null, `#${targetId}`);
                    
                    // 顯示區域指示器
                    sectionIndicator.textContent = targetSection.querySelector('h2').textContent;
                    sectionIndicator.classList.add('visible');
                    
                    // 3秒後隱藏指示器
                    setTimeout(function() {
                        sectionIndicator.classList.remove('visible');
                    }, 3000);
                }
            });
        });
        
        // 監聽滾動事件
        window.addEventListener('scroll', function() {
            // 顯示/隱藏返回頂部按鈕
            if (window.pageYOffset > 300) {
                backToTop.classList.add('visible');
            } else {
                backToTop.classList.remove('visible');
            }
            
            // 確定當前可見區塊
            let currentSectionId = '';
            sections.forEach(section => {
                const sectionTop = section.offsetTop - 100;
                const sectionHeight = section.offsetHeight;
                
                if (window.pageYOffset >= sectionTop && window.pageYOffset < sectionTop + sectionHeight) {
                    currentSectionId = section.getAttribute('id');
                }
            });
            
            // 更新活動導航連結樣式
            navLinks.forEach(link => {
                link.classList.remove('active');
                if (link.getAttribute('href') === `#${currentSectionId}`) {
                    link.classList.add('active');
                }
            });
        });
        
        // 返回頂部按鈕點擊事件
        backToTop.addEventListener('click', function(e) {
            e.preventDefault();
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });
        
        // 處理頁面載入時的錨點
        if (window.location.hash) {
            // 延遲執行以確保頁面完全載入
            setTimeout(function() {
                const targetId = window.location.hash.substring(1);
                const targetSection = document.getElementById(targetId);
                
                if (targetSection) {
                    const offsetTop = targetSection.offsetTop - 60;
                    window.scrollTo({
                        top: offsetTop,
                        behavior: 'smooth'
                    });
                }
            }, 100);
        }
        
        // 為所有卡片添加懸停效果
        const cards = document.querySelectorAll('.hotel-card, .day-card, .list-card, .tip-card');
        cards.forEach(card => {
            card.addEventListener('mouseenter', function() {
                this.style.transform = 'translateY(-5px)';
                this.style.boxShadow = '0 8px 24px rgba(0,0,0,0.15)';
            });
            
            card.addEventListener('mouseleave', function() {
                this.style.transform = '';
                this.style.boxShadow = '';
            });
        });
        
        // 添加頁面預加載功能
        function preloadSections() {
            // 獲取所有延遲加載的圖片
            const lazyImages = document.querySelectorAll('[loading="lazy"]');
            
            // 創建Intersection Observer來監控元素是否進入視口
            const imageObserver = new IntersectionObserver((entries, observer) => {
                entries.forEach(entry => {
                    // 當元素進入視口時
                    if (entry.isIntersecting) {
                        const img = entry.target;
                        // 設置背景圖片URL
                        const bgUrl = img.style.backgroundImage;
                        if (bgUrl) {
                            // 預加載圖片
                            const tempImg = new Image();
                            // 從url("...") 中提取URL
                            const url = bgUrl.match(/url\(['"]?(.*?)['"]?\)/)[1];
                            tempImg.src = url;
                        }
                        // 停止觀察此元素
                        observer.unobserve(img);
                    }
                });
            });
            
            // 開始觀察所有延遲加載的圖片
            lazyImages.forEach(img => {
                imageObserver.observe(img);
            });
        }
        
        // 執行預加載
        preloadSections();
        
        // 支持打印功能的優化
        const printButton = document.createElement('button');
        printButton.textContent = '打印行程';
        printButton.style.position = 'fixed';
        printButton.style.bottom = '30px';
        printButton.style.left = '30px';
        printButton.style.padding = '10px 15px';
        printButton.style.backgroundColor = '#0a9396';
        printButton.style.color = 'white';
        printButton.style.border = 'none';
        printButton.style.borderRadius = '5px';
        printButton.style.cursor = 'pointer';
        printButton.style.zIndex = '999';
        printButton.style.boxShadow = '0 2px 10px rgba(0,0,0,0.2)';
        
        printButton.addEventListener('mouseenter', function() {
            this.style.backgroundColor = '#ee9b00';
        });
        
        printButton.addEventListener('mouseleave', function() {
            this.style.backgroundColor = '#0a9396';
        });
        
        printButton.addEventListener('click', function() {
            window.print();
        });
        
        document.body.appendChild(printButton);
        
        // 修復Safari瀏覽器中的錨點問題
        if (/^((?!chrome|android).)*safari/i.test(navigator.userAgent)) {
            navLinks.forEach(link => {
                const originalHandler = link.onclick;
                link.onclick = function(e) {
                    e.preventDefault();
                    const targetId = this.getAttribute('href').substring(1);
                    const targetElement = document.getElementById(targetId);
                    if (targetElement) {
                        setTimeout(function() {
                            const offsetTop = targetElement.offsetTop - 60;
                            window.scrollTo(0, offsetTop);
                        }, 10);
                    }
                    return false;
                };
            });
        }
        
        // 為每個時間線項目添加動畫效果
        const timelineItems = document.querySelectorAll('.timeline-item');
        
        const timelineObserver = new IntersectionObserver((entries, observer) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateX(0)';
                    observer.unobserve(entry.target);
                }
            });
        }, { threshold: 0.2 });
        
        timelineItems.forEach(item => {
            item.style.opacity = '0';
            item.style.transform = 'translateX(-20px)';
            item.style.transition = 'all 0.5s ease';
            timelineObserver.observe(item);
        });
        
        // 檢測網絡連接狀態
        window.addEventListener('online', updateNetworkStatus);
        window.addEventListener('offline', updateNetworkStatus);
        
        function updateNetworkStatus() {
            if (!navigator.onLine) {
                alert('您似乎已離線。部分功能可能無法正常工作，但您仍可查看已加載的行程內容。');
            }
        }
        
        // 初始檢查
        updateNetworkStatus();
        
        // 添加頁面可見性變化處理
        document.addEventListener('visibilitychange', function() {
            if (document.visibilityState === 'visible') {
                // 頁面變為可見時，刷新某些數據或UI
                updateNetworkStatus();
            }
        });
        
        // 處理頁面大小變化
        window.addEventListener('resize', function() {
            // 在移動設備上調整導航欄
            if (window.innerWidth <= 768) {
                document.getElementById('main-nav').style.overflowX = 'auto';
            } else {
                document.getElementById('main-nav').style.overflowX = 'visible';
            }
        });
        
        // 初始調用一次
        if (window.innerWidth <= 768) {
            document.getElementById('main-nav').style.overflowX = 'auto';
        }
        
        // 添加錯誤處理
        window.onerror = function(message, source, lineno, colno, error) {
            console.error('頁面發生錯誤:', message);
            // 如果是導航相關錯誤，嘗試修復
            if (message.includes('scroll') || message.includes('navigate')) {
                // 重置滾動行為
                window.scrollTo(0, 0);
                return true; // 防止錯誤冒泡
            }
            return false; // 允許默認錯誤處理
        };
    });
</script>
</body>
</html>
