<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hành Trình Chạm Tới Tổ Ấm - Springland Group</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; }
        .gradient-bg { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); }
        .testimonial-card { 
            backdrop-filter: blur(10px);
            background: rgba(255, 255, 255, 0.1);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        .floating-animation {
            animation: float 6s ease-in-out infinite;
        }
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
        }
        .fade-in {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.8s ease-out;
        }
        .fade-in.visible {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Hero Section -->
    <section class="gradient-bg min-h-screen flex items-center justify-center relative overflow-hidden">
        <div class="absolute inset-0 bg-black bg-opacity-20"></div>
        
        <!-- Floating Elements -->
        <div class="absolute top-20 left-10 floating-animation">
            <div class="w-16 h-16 bg-white bg-opacity-20 rounded-full"></div>
        </div>
        <div class="absolute bottom-32 right-16 floating-animation" style="animation-delay: -2s;">
            <div class="w-12 h-12 bg-white bg-opacity-15 rounded-full"></div>
        </div>
        <div class="absolute top-1/3 right-1/4 floating-animation" style="animation-delay: -4s;">
            <div class="w-8 h-8 bg-white bg-opacity-25 rounded-full"></div>
        </div>

        <div class="container mx-auto px-6 text-center relative z-10">
            <h1 class="text-5xl md:text-7xl font-bold text-white mb-8 leading-tight fade-in">
                Hành Trình Chạm Tới<br>
                <span class="text-yellow-300">Tổ Ấm</span>
            </h1>
            <p class="text-xl md:text-2xl text-white mb-12 max-w-3xl mx-auto leading-relaxed fade-in" style="animation-delay: 0.2s;">
                Bạn Có Là Người Tiếp Theo?
            </p>
            <button class="bg-yellow-400 hover:bg-yellow-500 text-gray-900 font-semibold px-12 py-4 rounded-full text-lg transition-all duration-300 transform hover:scale-105 shadow-2xl fade-in" style="animation-delay: 0.4s;">
                Bắt Đầu Hành Trình 🏠
            </button>
        </div>
    </section>

    <!-- Story Section -->
    <section class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="max-w-4xl mx-auto">
                <h2 class="text-4xl md:text-5xl font-bold text-gray-800 mb-12 text-center fade-in">
                    Bạn Không Đơn Độc
                </h2>
                
                <div class="prose prose-lg max-w-none text-gray-700 leading-relaxed fade-in">
                    <p class="text-xl mb-8">
                        Chăm chỉ, đã tích góp được chút ít nhưng lúc nào cũng băn khoăn: <em>"Liệu mình có thật sự sở hữu được nhà ở Úc?"</em>, <em>"Mình nên bắt đầu từ đâu?"</em>, <em>"lỡ may..."</em> nghĩ đến đó rồi tặc lưỡi cho qua, nhưng thời gian chỉ làm cho giấc mơ ngày một không giữ nổi.
                    </p>
                    
                    <div class="bg-blue-50 p-8 rounded-2xl mb-12">
                        <p class="text-xl font-medium text-blue-800 mb-4">
                            Bạn không đơn độc. Rất nhiều người chúng tôi gặp đã từng như bạn – lo lắng, nghi ngờ bản thân, bối rối giữa hàng trăm lựa chọn.
                        </p>
                        <p class="text-lg text-blue-700">
                            Nhưng họ đã làm được. Và hôm nay, họ đang sống trong chính tổ ấm mơ ước của mình.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Pain Points Section -->
    <section class="py-20 bg-gray-100">
        <div class="container mx-auto px-6">
            <div class="max-w-5xl mx-auto">
                <h2 class="text-4xl md:text-5xl font-bold text-gray-800 mb-16 text-center fade-in">
                    Họ Đã Từng Như Bạn – Và Bạn Có Từng Như Họ?
                </h2>
                
                <div class="grid md:grid-cols-2 gap-12 mb-16">
                    <div class="space-y-8">
                        <div class="flex items-start space-x-4 fade-in">
                            <div class="w-3 h-3 bg-red-500 rounded-full mt-2 flex-shrink-0"></div>
                            <p class="text-lg text-gray-700">Những đêm trằn trọc vì không biết phải bắt đầu từ đâu.</p>
                        </div>
                        
                        <div class="flex items-start space-x-4 fade-in">
                            <div class="w-3 h-3 bg-red-500 rounded-full mt-2 flex-shrink-0"></div>
                            <p class="text-lg text-gray-700">Những lần đi ngang qua bảng "For Sale" hay đến tân gia nhà bạn rồi tự nhủ: <em>"Chắc mình chưa đủ khả năng..."</em></p>
                        </div>
                        
                        <div class="flex items-start space-x-4 fade-in">
                            <div class="w-3 h-3 bg-red-500 rounded-full mt-2 flex-shrink-0"></div>
                            <p class="text-lg text-gray-700">Những lúc nghe tin giá nhà tăng mà tim như thắt lại: <em>"Giấc mơ ngày một xa vời"</em></p>
                        </div>
                    </div>
                    
                    <div class="bg-white p-8 rounded-2xl shadow-lg fade-in">
                        <h3 class="text-2xl font-semibold text-gray-800 mb-6">Họ từng mang trong mình:</h3>
                        <div class="space-y-4">
                            <div class="flex items-center space-x-3">
                                <span class="text-2xl">💭</span>
                                <span class="text-gray-700">Giấc mơ tổ ấm</span>
                            </div>
                            <div class="flex items-center space-x-3">
                                <span class="text-2xl">😰</span>
                                <span class="text-gray-700">Tiếng nói nghi ngờ</span>
                            </div>
                            <div class="flex items-center space-x-3">
                                <span class="text-2xl">😔</span>
                                <span class="text-gray-700">Áp lực hoàn cảnh</span>
                            </div>
                            <div class="flex items-center space-x-3">
                                <span class="text-2xl">😨</span>
                                <span class="text-gray-700">Nỗi sợ không tên</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Customer Stories -->
    <section class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="max-w-6xl mx-auto">
                <h2 class="text-4xl md:text-5xl font-bold text-gray-800 mb-16 text-center fade-in">
                    Những Câu Chuyện Thật
                </h2>
                
                <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8 mb-16">
                    <div class="bg-gradient-to-br from-pink-100 to-purple-100 p-6 rounded-2xl fade-in">
                        <div class="text-4xl mb-4">👨‍💼</div>
                        <h3 class="font-semibold text-gray-800 mb-2">Tiến Kiều</h3>
                        <p class="text-sm text-gray-600">Chỉ có vài chục ngàn tiền tiết kiệm sau nhiều năm đi làm thuê</p>
                    </div>
                    
                    <div class="bg-gradient-to-br from-blue-100 to-cyan-100 p-6 rounded-2xl fade-in">
                        <div class="text-4xl mb-4">🤱</div>
                        <h3 class="font-semibold text-gray-800 mb-2">Trâm Vân, Quỳnh</h3>
                        <p class="text-sm text-gray-600">Cô gái trẻ một mình nơi xứ lạ, mang thai đứa con đầu lòng</p>
                    </div>
                    
                    <div class="bg-gradient-to-br from-green-100 to-emerald-100 p-6 rounded-2xl fade-in">
                        <div class="text-4xl mb-4">👩‍👧‍👦</div>
                        <h3 class="font-semibold text-gray-800 mb-2">Nhi</h3>
                        <p class="text-sm text-gray-600">Mẹ đơn thân vừa làm vừa nuôi 3 người con nhỏ</p>
                    </div>
                    
                    <div class="bg-gradient-to-br from-yellow-100 to-orange-100 p-6 rounded-2xl fade-in">
                        <div class="text-4xl mb-4">💑</div>
                        <h3 class="font-semibold text-gray-800 mb-2">Lài Lê</h3>
                        <p class="text-sm text-gray-600">Đôi trẻ chưa tổ chức lễ cưới, chỉ mong có mái nhà nhỏ</p>
                    </div>
                </div>
                
                <div class="text-center mb-16">
                    <div class="bg-red-50 border-l-4 border-red-400 p-8 rounded-r-2xl max-w-2xl mx-auto fade-in">
                        <h3 class="text-2xl font-bold text-red-800 mb-4">Điểm chung giữa họ và bạn?</h3>
                        <p class="text-xl text-red-700 mb-2">Đều từng phân vân. Đều từng sợ mình</p>
                        <p class="text-3xl font-bold text-red-800">"KHÔNG ĐỦ"</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="py-20 gradient-bg relative overflow-hidden">
        <div class="absolute inset-0 bg-black bg-opacity-30"></div>
        <div class="container mx-auto px-6 relative z-10">
            <div class="max-w-6xl mx-auto">
                <h2 class="text-4xl md:text-5xl font-bold text-white mb-16 text-center fade-in">
                    Từ Ước Mơ Đến Hiện Thực
                </h2>
                
                <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <div class="testimonial-card p-8 rounded-2xl fade-in">
                        <div class="text-4xl mb-4">💬</div>
                        <p class="text-white mb-6 leading-relaxed">
                            "Khi đứng trước cửa nhà mới, tay cầm chìa khoá, mình không tin nổi điều này là thật. Chỉ 8 tháng trước, mình còn nghĩ mình sẽ thuê nhà thêm vài năm nữa..."
                        </p>
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-yellow-400 rounded-full flex items-center justify-center mr-4">
                                <span class="text-gray-800 font-bold">Q</span>
                            </div>
                            <div>
                                <p class="text-white font-semibold">Quỳnh</p>
                                <p class="text-gray-300 text-sm">Mẹ bỉm sữa</p>
                            </div>
                        </div>
                    </div>
                    
                    <div class="testimonial-card p-8 rounded-2xl fade-in">
                        <div class="text-4xl mb-4">💬</div>
                        <p class="text-white mb-6 leading-relaxed">
                            "Không phải lúc nào cũng dễ dàng. Có lúc muốn bỏ cuộc. Nhưng may mắn là Springland Group luôn ở đó, hướng dẫn từng bước, động viên mình."
                        </p>
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-blue-400 rounded-full flex items-center justify-center mr-4">
                                <span class="text-white font-bold">T</span>
                            </div>
                            <div>
                                <p class="text-white font-semibold">Trúc</p>
                                <p class="text-gray-300 text-sm">Mẹ đơn thân</p>
                            </div>
                        </div>
                    </div>
                    
                    <div class="testimonial-card p-8 rounded-2xl fade-in">
                        <div class="text-4xl mb-4">💬</div>
                        <p class="text-white mb-6 leading-relaxed">
                            "Mình từng nghĩ: nhà là giấc mơ của người khác. Nhưng giờ đây khi nhìn con chạy chơi trong sân nhà mới, mình hiểu rằng: mình xứng đáng với điều này."
                        </p>
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-green-400 rounded-full flex items-center justify-center mr-4">
                                <span class="text-gray-800 font-bold">L</span>
                            </div>
                            <div>
                                <p class="text-white font-semibold">Lài</p>
                                <p class="text-gray-300 text-sm">Gia đình trẻ</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="text-center mt-16">
                    <div class="bg-white bg-opacity-20 backdrop-filter backdrop-blur-lg p-8 rounded-2xl max-w-2xl mx-auto fade-in">
                        <h3 class="text-2xl font-bold text-white mb-4">🎥 Xem Video Câu Chuyện Thật</h3>
                        <p class="text-white mb-6">Hành trình của những người đã từng hoang mang như bạn, nhưng nay đã sở hữu tổ ấm riêng tại Úc.</p>
                        <button class="bg-red-500 hover:bg-red-600 text-white font-semibold px-8 py-3 rounded-full transition-all duration-300 transform hover:scale-105">
                            ▶️ Xem Ngay
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Call to Action -->
    <section class="py-20 bg-yellow-400">
        <div class="container mx-auto px-6 text-center">
            <div class="max-w-4xl mx-auto">
                <h2 class="text-4xl md:text-5xl font-bold text-gray-800 mb-8 fade-in">
                    💡 Họ Không Phải "Người Giỏi Nhất"
                </h2>
                <p class="text-xl text-gray-700 mb-8 fade-in">
                    Họ chỉ dũng cảm làm bước đầu tiên. Và hôm nay, chính bạn có thể là người viết tiếp câu chuyện đó.
                </p>
                
                <div class="bg-white p-8 rounded-2xl shadow-2xl mb-12 fade-in">
                    <h3 class="text-2xl font-bold text-gray-800 mb-6">Bắt Đầu Hành Trình Của Bạn</h3>
                    <div class="grid md:grid-cols-3 gap-6 mb-8">
                        <div class="text-center">
                            <div class="w-16 h-16 bg-blue-100 rounded-full flex items-center justify-center mx-auto mb-4">
                                <span class="text-2xl">💬</span>
                            </div>
                            <h4 class="font-semibold text-gray-800 mb-2">Cuộc Trò Chuyện</h4>
                            <p class="text-gray-600 text-sm">Chia sẻ tình hình và mong muốn của bạn</p>
                        </div>
                        <div class="text-center">
                            <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-4">
                                <span class="text-2xl">🎯</span>
                            </div>
                            <h4 class="font-semibold text-gray-800 mb-2">Tư Vấn Cá Nhân</h4>
                            <p class="text-gray-600 text-sm">Lộ trình phù hợp với hoàn cảnh riêng</p>
                        </div>
                        <div class="text-center">
                            <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-4">
                                <span class="text-2xl">🏠</span>
                            </div>
                            <h4 class="font-semibold text-gray-800 mb-2">Hiện Thực Hóa</h4>
                            <p class="text-gray-600 text-sm">Đồng hành đến khi cầm chìa khóa</p>
                        </div>
                    </div>
                    
                    <button class="bg-gradient-to-r from-purple-600 to-blue-600 hover:from-purple-700 hover:to-blue-700 text-white font-bold px-12 py-4 rounded-full text-lg transition-all duration-300 transform hover:scale-105 shadow-xl">
                        Đặt Câu Hỏi Đầu Tiên 🚀
                    </button>
                </div>
                
                <p class="text-lg text-gray-700 italic fade-in">
                    "Liệu mình có thể bắt đầu, dù chưa đủ hoàn hảo?"
                </p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-12">
        <div class="container mx-auto px-6 text-center">
            <div class="mb-8">
                <h3 class="text-2xl font-bold mb-4">Springland Group</h3>
                <p class="text-gray-400 max-w-2xl mx-auto">
                    Đồng hành cùng bạn trên hành trình chạm tới tổ ấm. Không chỉ là mua nhà, mà là xây dựng tương lai.
                </p>
            </div>
            
            <div class="border-t border-gray-700 pt-8">
                <p class="text-gray-400">
                    © 2024 Springland Group. Tất cả quyền được bảo lưu.
                </p>
            </div>
        </div>
    </footer>

    <script>
        // Intersection Observer for fade-in animations
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, observerOptions);

        // Observe all fade-in elements
        document.querySelectorAll('.fade-in').forEach(el => {
            observer.observe(el);
        });

        // Smooth scrolling for buttons
        document.querySelectorAll('button').forEach(button => {
            button.addEventListener('click', (e) => {
                // Add click effect
                button.style.transform = 'scale(0.95)';
                setTimeout(() => {
                    button.style.transform = '';
                }, 150);
            });
        });

        // Add parallax effect to hero section
        window.addEventListener('scroll', () => {
            const scrolled = window.pageYOffset;
            const parallax = document.querySelector('.gradient-bg');
            const speed = scrolled * 0.5;
            parallax.style.transform = `translateY(${speed}px)`;
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'969a3723e015e2ee',t:'MTc1NDI3MDI0OS4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
