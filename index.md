---
title: "YOUR-TITLE"
date: 2025-08-19
---

  酒店电子设备使用指南  \* { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', 'PingFang SC', 'Microsoft YaHei', sans-serif; } :root { --primary: #005792; --primary-light: #0077b6; --secondary: #00b4d8; --accent: #ff6b6b; --light: #f8f9fa; --dark: #212529; --gray: #6c757d; --light-gray: #e9ecef; --card-shadow: 0 10px 30px rgba(0, 0, 0, 0.08); --transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275); } body { background: linear-gradient(135deg, #f0f8ff 0%, #e6f7ff 100%); color: var(--dark); line-height: 1.6; min-height: 100vh; padding-bottom: 20px; background-attachment: fixed; } .container { max-width: 1200px; margin: 0 auto; padding: 20px; } header { background: linear-gradient(120deg, var(--primary) 0%, var(--primary-light) 100%); color: white; padding: 25px 0; text-align: center; margin-bottom: 40px; border-radius: 0 0 30px 30px; box-shadow: 0 6px 20px rgba(0, 87, 146, 0.3); position: relative; overflow: hidden; } header::before { content: ""; position: absolute; top: -50px; left: -50px; width: 200px; height: 200px; border-radius: 50%; background: rgba(255, 255, 255, 0.1); } header::after { content: ""; position: absolute; bottom: -80px; right: -30px; width: 250px; height: 250px; border-radius: 50%; background: rgba(255, 255, 255, 0.08); } .logo-container { display: flex; align-items: center; justify-content: center; gap: 20px; position: relative; z-index: 2; margin-bottom: 15px; } .logo { width: 60px; height: 60px; background: white; border-radius: 18px; display: flex; align-items: center; justify-content: center; box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15); transform: rotate(45deg); transition: var(--transition); } .logo:hover { transform: rotate(0) scale(1.1); } .logo i { font-size: 28px; color: var(--primary); transform: rotate(-45deg); transition: var(--transition); } .logo:hover i { transform: rotate(0); } h1 { font-size: 2.8rem; font-weight: 800; text-shadow: 0 3px 8px rgba(0, 0, 0, 0.2); margin-bottom: 10px; position: relative; z-index: 2; letter-spacing: -0.5px; } .subtitle { font-size: 1.2rem; opacity: 0.9; max-width: 700px; margin: 0 auto; position: relative; z-index: 2; } .intro { text-align: center; margin-bottom: 40px; padding: 0 20px; position: relative; } .intro-card { background: rgba(255, 255, 255, 0.92); backdrop-filter: blur(10px); border-radius: 20px; padding: 35px 40px; box-shadow: var(--card-shadow); max-width: 800px; margin: 0 auto; border: 1px solid rgba(0, 180, 216, 0.1); } .intro p { font-size: 1.15rem; margin-bottom: 15px; color: var(--gray); line-height: 1.8; } .highlight { background: linear-gradient(120deg, rgba(0, 180, 216, 0.15), transparent); padding: 3px 8px; border-radius: 6px; font-weight: 600; color: var(--primary); } .search-filter { display: flex; flex-wrap: wrap; gap: 20px; margin-bottom: 40px; background: rgba(255, 255, 255, 0.92); backdrop-filter: blur(10px); padding: 25px; border-radius: 20px; box-shadow: var(--card-shadow); border: 1px solid rgba(0, 180, 216, 0.1); max-width: 1000px; margin: 0 auto 40px; } .search-box { flex: 1; min-width: 250px; position: relative; } .search-box input { width: 100%; padding: 16px 20px 16px 55px; border: 2px solid #d0ebff; border-radius: 15px; font-size: 1.05rem; transition: var(--transition); background: rgba(240, 248, 255, 0.5); } .search-box input:focus { outline: none; border-color: var(--secondary); box-shadow: 0 0 0 4px rgba(0, 180, 216, 0.25); background: white; } .search-box i { position: absolute; left: 25px; top: 50%; transform: translateY(-50%); color: var(--primary); font-size: 1.2rem; } .category-filter { display: flex; flex-wrap: wrap; gap: 12px; justify-content: center; width: 100%; margin-top: 10px; } .category-btn { padding: 12px 24px; background: #e3f8ff; border: none; border-radius: 12px; color: var(--primary); font-weight: 600; cursor: pointer; transition: var(--transition); font-size: 1rem; display: flex; align-items: center; gap: 8px; } .category-btn:hover { transform: translateY(-3px); box-shadow: 0 5px 15px rgba(0, 180, 216, 0.2); background: var(--secondary); color: white; } .category-btn.active { background: var(--primary); color: white; box-shadow: 0 5px 15px rgba(0, 87, 146, 0.3); } .devices-container { display: grid; grid-template-columns: repeat(auto-fill, minmax(320px, 1fr)); gap: 30px; margin-bottom: 40px; } .device-card { background: linear-gradient(135deg, rgba(255, 255, 255, 0.95) 0%, rgba(248, 249, 250, 0.95) 100%); border-radius: 20px; overflow: hidden; box-shadow: var(--card-shadow); transition: var(--transition); cursor: pointer; position: relative; transform: translateY(0); border: 1px solid rgba(0, 180, 216, 0.08); } .device-card:hover { transform: translateY(-10px) scale(1.02); box-shadow: 0 20px 40px rgba(0, 0, 0, 0.15); border-color: rgba(0, 180, 216, 0.3); } .device-thumbnail { position: relative; height: 200px; } .device-thumbnail::before { content: ""; position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: linear-gradient(45deg, var(--primary), var(--secondary)); opacity: 0.7; z-index: 1; } .device-thumbnail img { width: 100%; height: 100%; object-fit: cover; } .device-name { position: absolute; bottom: 20px; left: 20px; color: white; font-size: 1.6rem; font-weight: 700; z-index: 2; text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3); } .play-icon { position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); width: 70px; height: 70px; background: rgba(255, 255, 255, 0.9); border-radius: 50%; display: flex; align-items: center; justify-content: center; transition: var(--transition); z-index: 2; box-shadow: 0 5px 20px rgba(0, 0, 0, 0.2); } .play-icon i { color: var(--primary); font-size: 28px; margin-left: 5px; transition: var(--transition); } .device-card:hover .play-icon { background: var(--accent); transform: translate(-50%, -50%) scale(1.1); } .device-card:hover .play-icon i { color: white; } .device-info { padding: 25px; } .device-info h3 { margin-bottom: 15px; color: var(--primary); font-size: 1.5rem; display: flex; align-items: center; gap: 10px; } .device-info h3 i { color: var(--secondary); } .device-info p { color: var(--gray); font-size: 1.05rem; margin-bottom: 20px; line-height: 1.7; } .device-category { display: inline-flex; align-items: center; background: #e3f8ff; color: var(--primary); padding: 8px 18px; border-radius: 50px; font-size: 0.9rem; font-weight: 600; gap: 8px; } footer { text-align: center; padding: 30px; background: linear-gradient(120deg, var(--primary) 0%, var(--primary-light) 100%); color: white; border-radius: 30px 30px 0 0; margin-top: 60px; position: relative; overflow: hidden; } footer::before { content: ""; position: absolute; top: -50px; left: 0; width: 100%; height: 100px; background: white; transform: skewY(-3deg); } .footer-content { max-width: 800px; margin: 0 auto; position: relative; z-index: 2; } .contact-info { display: flex; justify-content: center; gap: 40px; margin: 30px 0; flex-wrap: wrap; } .contact-item { display: flex; align-items: center; gap: 12px; background: rgba(255, 255, 255, 0.15); padding: 12px 25px; border-radius: 50px; backdrop-filter: blur(5px); transition: var(--transition); } .contact-item:hover { background: rgba(255, 255, 255, 0.25); transform: translateY(-3px); } .contact-item i { font-size: 1.3rem; } .copyright { margin-top: 20px; opacity: 0.8; font-size: 0.95rem; } /\* 视频模态框 \*/ .video-modal { display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.95); z-index: 1000; align-items: center; justify-content: center; } .modal-content { width: 90%; max-width: 900px; position: relative; background: #111; border-radius: 20px; overflow: hidden; box-shadow: 0 20px 50px rgba(0, 0, 0, 0.5); } .close-modal { position: absolute; top: 20px; right: 20px; color: white; font-size: 2rem; cursor: pointer; z-index: 10; background: rgba(255, 255, 255, 0.15); width: 50px; height: 50px; border-radius: 50%; display: flex; align-items: center; justify-content: center; transition: var(--transition); } .close-modal:hover { background: var(--accent); transform: rotate(90deg); } .video-container { position: relative; padding-top: 56.25%; /\* 16:9 比例 \*/ } .video-container iframe { position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: none; } .video-info { padding: 25px; color: white; background: rgba(30, 30, 30, 0.9); } .video-info h3 { font-size: 1.8rem; margin-bottom: 15px; color: var(--secondary); } .video-info p { color: #ccc; font-size: 1.1rem; line-height: 1.7; } /\* 响应式设计 \*/ @media (max-width: 768px) { .devices-container { grid-template-columns: 1fr; } h1 { font-size: 2.2rem; } .search-filter { padding: 20px; } .category-btn { padding: 10px 18px; font-size: 0.95rem; } .device-card { max-width: 450px; margin: 0 auto; } }

酒店电子设备使用指南
==========

轻松掌握酒店设备使用方法，享受舒适入住体验

欢迎使用尊贵酒店电子设备指南系统！我们精心准备了各类电子设备的操作视频，帮助您快速掌握设备使用方法。

只需点击设备卡片，即可观看对应的高清使用视频，让您的入住体验更加轻松舒适。

全部设备 空调系统 娱乐设备 卫浴设备 照明系统 安全设备

![空调系统](https://images.unsplash.com/photo-1585123334904-845d60e97b29?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80)

空调系统

### 空调系统

学习如何调节房间温度、风速和各种运行模式，让您的住宿环境始终保持舒适状态。

环境控制

![智能电视](https://images.unsplash.com/photo-1574375927938-d5a98e8ffe85?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80)

智能电视

### 智能电视

了解如何操作电视、访问电视频道、流媒体服务和投屏功能，享受丰富娱乐体验。

娱乐设备

![灯光控制](https://images.unsplash.com/photo-1581093458799-7e0a062a7c16?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80)

灯光控制

### 灯光控制系统

掌握房间灯光的各种控制方式、场景模式和定时功能，营造理想的光线氛围。

照明系统

![电动窗帘](https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80)

电动窗帘

### 电动窗帘

学习如何操作电动窗帘、设置定时功能和调节透光度，轻松控制自然光线。

环境控制

![智能马桶](https://images.unsplash.com/photo-1584622650111-993a426fbf0a?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80)

智能马桶

### 智能马桶

了解智能马桶的各种功能、清洁选项和使用注意事项，享受科技带来的舒适体验。

卫浴设备

![保险箱](https://images.unsplash.com/photo-1584438784894-089d6a62b8fa?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80)

电子保险箱

### 电子保险箱

学习如何设置密码、使用和重置房间内的电子保险箱，保障您的贵重物品安全。

安全设备

Ascott

需要更多帮助?

我们的服务团队24小时为您提供支持

前台电话: "0"

客房服务: "5"

© 2025 让科技服务您的舒适体验

×

// 打开模态框并加载视频 function openModal(title, videoUrl, description) { document.getElementById('videoTitle').textContent = title; document.getElementById('videoDescription').textContent = description; document.getElementById('videoFrame').src = videoUrl; document.getElementById('videoModal').style.display = 'flex'; document.body.style.overflow = 'hidden'; } // 关闭模态框 function closeModal() { document.getElementById('videoModal').style.display = 'none'; document.getElementById('videoFrame').src = ''; document.body.style.overflow = 'auto'; } // 点击模态框外部关闭 window.onclick = function(event) { const modal = document.getElementById('videoModal'); if (event.target == modal) { closeModal(); } } // 类别筛选功能 const categoryBtns = document.querySelectorAll('.category-btn'); categoryBtns.forEach(btn => { btn.addEventListener('click', () => { // 移除所有按钮的active类 categoryBtns.forEach(b => b.classList.remove('active')); // 为当前点击的按钮添加active类 btn.classList.add('active'); // 这里可以添加实际的筛选逻辑 console.log('筛选类别:', btn.textContent); }); }); // 搜索功能 const searchInput = document.querySelector('.search-box input'); searchInput.addEventListener('input', (e) => { console.log('搜索关键词:', e.target.value); // 这里可以添加实际的搜索逻辑 }); // 添加滚动动画效果 document.addEventListener('DOMContentLoaded', function() { const deviceCards = document.querySelectorAll('.device-card'); const observer = new IntersectionObserver((entries) => { entries.forEach(entry => { if (entry.isIntersecting) { entry.target.style.opacity = 1; entry.target.style.transform = 'translateY(0)'; } }); }, { threshold: 0.1 }); deviceCards.forEach(card => { card.style.opacity = 0; card.style.transform = 'translateY(30px)'; card.style.transition = 'opacity 0.6s ease, transform 0.6s ease'; observer.observe(card); }); });
