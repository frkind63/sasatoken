<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SASA - Cope Together, Earn Together | Honest Crypto Community</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
        }
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }
        .float { animation: float 3s ease-in-out infinite; }
        .fade-in-up { animation: fadeInUp 0.8s ease-out forwards; }
        .pulse { animation: pulse 2s ease-in-out infinite; }
        .gradient-bg {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        .gradient-text {
            background: linear-gradient(135deg, #ffd700 0%, #ff6b9d 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        .glass {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        .tier-card {
            background: linear-gradient(135deg, rgba(102, 126, 234, 0.15) 0%, rgba(118, 75, 162, 0.15) 100%);
            border: 2px solid rgba(167, 139, 250, 0.3);
            transition: all 0.3s ease;
        }
        .tier-card:hover {
            border-color: rgba(167, 139, 250, 0.6);
            transform: translateY(-5px);
        }
    </style>
</head>
<body class="bg-gray-900 text-white">
    
    <!-- Header -->
    <nav class="fixed w-full z-50 glass">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <div class="flex items-center">
                    <span class="text-2xl font-bold">🤖 SASA</span>
                </div>
                <div class="hidden md:flex space-x-6">
                    <a href="#about" class="hover:text-purple-400 transition">About</a>
                    <a href="#contribute" class="hover:text-purple-400 transition">Contribute</a>
                    <a href="#tiers" class="hover:text-purple-400 transition">Recognition</a>
                    <a href="#how" class="hover:text-purple-400 transition">How to Buy</a>
                </div>
                <button class="bg-gradient-to-r from-purple-600 to-pink-600 hover:opacity-90 px-6 py-2 rounded-full font-semibold transition">
                    Join $SASA
                </button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="gradient-bg min-h-screen flex items-center justify-center relative overflow-hidden pt-16">
        <div class="absolute inset-0 opacity-20">
            <div class="absolute top-20 left-10 text-6xl">💜</div>
            <div class="absolute top-40 right-20 text-6xl">🤝</div>
            <div class="absolute bottom-40 left-20 text-6xl">🏆</div>
            <div class="absolute bottom-20 right-40 text-6xl">✨</div>
        </div>
        
        <div class="max-w-6xl mx-auto px-4 text-center z-10">
            <div class="float mb-8">
                <svg viewBox="0 0 500 500" xmlns="http://www.w3.org/2000/svg" class="w-64 h-64 mx-auto">
                    <circle cx="250" cy="250" r="240" fill="rgba(255,255,255,0.1)"/>
                    <g>
                        <rect x="150" y="180" width="200" height="180" rx="30" fill="#a8b3ff" stroke="#fff" stroke-width="4"/>
                        <line x1="250" y1="180" x2="250" y2="140" stroke="#fff" stroke-width="6" stroke-linecap="round"/>
                        <circle cx="250" cy="135" r="12" fill="#ff6b9d"/>
                        <ellipse cx="200" cy="240" rx="25" ry="30" fill="#fff"/>
                        <ellipse cx="205" cy="245" rx="12" ry="15" fill="#4a5568"/>
                        <path d="M 180 225 Q 200 215 220 225" stroke="#8b9cff" stroke-width="3" fill="none" stroke-linecap="round"/>
                        <ellipse cx="300" cy="240" rx="25" ry="30" fill="#fff"/>
                        <ellipse cx="295" cy="245" rx="12" ry="15" fill="#4a5568"/>
                        <path d="M 280 225 Q 300 215 320 225" stroke="#8b9cff" stroke-width="3" fill="none" stroke-linecap="round"/>
                        <ellipse cx="195" cy="270" rx="6" ry="12" fill="#64b5f6" opacity="0.7"/>
                        <ellipse cx="195" cy="285" rx="5" ry="8" fill="#64b5f6" opacity="0.7"/>
                        <ellipse cx="305" cy="275" rx="6" ry="12" fill="#64b5f6" opacity="0.7"/>
                        <path d="M 200 310 Q 250 290 300 310" stroke="#fff" stroke-width="6" fill="none" stroke-linecap="round"/>
                        <ellipse cx="130" cy="280" rx="20" ry="15" fill="#ff6b9d" opacity="0.4"/>
                        <ellipse cx="370" cy="280" rx="20" ry="15" fill="#ff6b9d" opacity="0.4"/>
                    </g>
                </svg>
            </div>
            <h1 class="text-6xl md:text-8xl font-bold mb-6 fade-in-up">
                SASA
            </h1>
            <p class="text-3xl md:text-5xl mb-4 fade-in-up font-bold gradient-text" style="animation-delay: 0.2s;">
                Cope Together, Earn Together
            </p>
            <p class="text-xl md:text-2xl mb-12 opacity-90 max-w-3xl mx-auto fade-in-up" style="animation-delay: 0.4s;">
                The honest crypto community where your losses find recognition, your contributions earn rewards, and support is always free. No unrealistic promises. Just real people, real support. 💜
            </p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center fade-in-up" style="animation-delay: 0.6s;">
                <button class="bg-white text-purple-600 px-8 py-4 rounded-full font-bold text-lg hover:scale-105 transition transform shadow-lg">
                    Join Community 🤝
                </button>
                <button class="glass px-8 py-4 rounded-full font-bold text-lg hover:scale-105 transition transform">
                    Learn More
                </button>
            </div>
            
            <!-- CA Box -->
            <div class="mt-12 glass p-6 rounded-2xl max-w-2xl mx-auto fade-in-up" style="animation-delay: 0.8s;">
                <p class="text-sm uppercase tracking-wider mb-2 opacity-75">Contract Address</p>
                <div class="flex items-center justify-between bg-black bg-opacity-30 p-4 rounded-lg">
                    <code class="text-sm sm:text-base break-all">Launching Soon 🚀</code>
                    <button class="ml-4 bg-purple-600 px-4 py-2 rounded-lg hover:bg-purple-700 transition flex-shrink-0">
                        Copy
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Core Values -->
    <section class="py-20 bg-gray-800">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-4xl md:text-5xl font-bold text-center mb-12">
                What Makes SASA <span class="gradient-text">Different</span>
            </h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="text-center p-6">
                    <div class="text-6xl mb-4">🤝</div>
                    <h3 class="text-2xl font-bold mb-3">Honesty First</h3>
                    <p class="text-gray-300 text-lg">No "100x guaranteed" BS. Just real rewards for real contributions. Transparent about risks and opportunities.</p>
                </div>
                <div class="text-center p-6">
                    <div class="text-6xl mb-4">💜</div>
                    <h3 class="text-2xl font-bold mb-3">Community Over Hype</h3>
                    <p class="text-gray-300 text-lg">Support is always free. Tokens are a bonus. We're here to help each other first, profit second.</p>
                </div>
                <div class="text-center p-6">
                    <div class="text-6xl mb-4">⚖️</div>
                    <h3 class="text-2xl font-bold mb-3">Fair & Flexible</h3>
                    <p class="text-gray-300 text-lg">Algorithmic distribution. No fixed promises we can't keep. Quality and consistency are rewarded.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-gray-900">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-5xl font-bold text-center mb-16">What is SASA?</h2>
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div>
                    <svg viewBox="0 0 500 500" xmlns="http://www.w3.org/2000/svg" class="w-80 h-80 mx-auto">
                        <circle cx="250" cy="250" r="240" fill="rgba(102,126,234,0.2)"/>
                        <g>
                            <rect x="150" y="180" width="200" height="180" rx="30" fill="#a8b3ff" stroke="#fff" stroke-width="4"/>
                            <line x1="250" y1="180" x2="250" y2="140" stroke="#fff" stroke-width="6" stroke-linecap="round"/>
                            <circle cx="250" cy="135" r="12" fill="#ff6b9d"/>
                            <ellipse cx="200" cy="240" rx="25" ry="30" fill="#fff"/>
                            <ellipse cx="205" cy="245" rx="12" ry="15" fill="#4a5568"/>
                            <path d="M 180 225 Q 200 215 220 225" stroke="#8b9cff" stroke-width="3" fill="none" stroke-linecap="round"/>
                            <ellipse cx="300" cy="240" rx="25" ry="30" fill="#fff"/>
                            <ellipse cx="295" cy="245" rx="12" ry="15" fill="#4a5568"/>
                            <path d="M 280 225 Q 300 215 320 225" stroke="#8b9cff" stroke-width="3" fill="none" stroke-linecap="round"/>
                            <ellipse cx="195" cy="270" rx="6" ry="12" fill="#64b5f6" opacity="0.7"/>
                            <ellipse cx="195" cy="285" rx="5" ry="8" fill="#64b5f6" opacity="0.7"/>
                            <ellipse cx="305" cy="275" rx="6" ry="12" fill="#64b5f6" opacity="0.7"/>
                            <path d="M 200 310 Q 250 290 300 310" stroke="#fff" stroke-width="6" fill="none" stroke-linecap="round"/>
                            <ellipse cx="130" cy="280" rx="20" ry="15" fill="#ff6b9d" opacity="0.4"/>
                            <ellipse cx="370" cy="280" rx="20" ry="15" fill="#ff6b9d" opacity="0.4"/>
                        </g>
                    </svg>
                </div>
                <div class="space-y-6">
                    <p class="text-xl leading-relaxed">
                        <strong class="text-purple-400">SASA</strong> is a community-first token where traders support each other through losses while earning recognition for their contributions.
                    </p>
                    <p class="text-lg text-gray-300 leading-relaxed">
                        We've all experienced crypto pain: rugs, liquidations, bad trades. Usually that pain just... hurts. With SASA, it becomes valuable — through shared stories, mutual support, and community rewards.
                    </p>
                    <p class="text-lg text-gray-300 leading-relaxed">
                        <strong class="text-purple-300">The model is simple:</strong> Be active, help others, share authentically. The community recognizes valuable contributions with token rewards. No fixed amounts, no unrealistic promises — just fair, transparent appreciation.
                    </p>
                    <div class="bg-purple-900 bg-opacity-30 p-6 rounded-xl border-l-4 border-purple-400">
                        <p class="text-lg font-semibold text-purple-200 mb-2">"Your losses have value here."</p>
                        <p class="text-gray-300">Not because we'll make you rich (maybe, maybe not), but because sharing and supporting has real worth. The tokens? A thank you. The community? Priceless. 💜</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contribute Section -->
    <section id="contribute" class="py-20 bg-gray-800">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-5xl font-bold text-center mb-6">How You <span class="gradient-text">Contribute & Earn</span></h2>
            <p class="text-xl text-gray-300 text-center mb-16 max-w-3xl mx-auto">
                Every authentic contribution is recognized. Rewards vary based on quality, verification, and community vote. Be real, be helpful, be rewarded. 🤝
            </p>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                
                <div class="glass p-8 rounded-2xl hover:scale-105 transition transform">
                    <div class="flex items-center mb-4">
                        <div class="text-5xl mr-4">📖</div>
                        <div>
                            <h3 class="text-2xl font-bold text-purple-300">Share Your Story</h3>
                            <p class="text-sm text-gray-400">Verified losses</p>
                        </div>
                    </div>
                    <p class="text-gray-200 mb-4">
                        Submit verified trading losses with proof. Best stories get community recognition and token rewards based on impact and authenticity.
                    </p>
                    <div class="text-sm text-purple-300">🏆 Recognition varies</div>
                </div>

                <div class="glass p-8 rounded-2xl hover:scale-105 transition transform">
                    <div class="flex items-center mb-4">
                        <div class="text-5xl mr-4">😂</div>
                        <div>
                            <h3 class="text-2xl font-bold text-purple-300">Create Content</h3>
                            <p class="text-sm text-gray-400">Memes & guides</p>
                        </div>
                    </div>
                    <p class="text-gray-200 mb-4">
                        Create memes, guides, analysis. Community votes determine value. Quality content consistently rewarded.
                    </p>
                    <div class="text-sm text-purple-300">🎨 Quality matters</div>
                </div>

                <div class="glass p-8 rounded-2xl hover:scale-105 transition transform">
                    <div class="flex items-center mb-4">
                        <div class="text-5xl mr-4">💬</div>
                        <div>
                            <h3 class="text-2xl font-bold text-purple-300">Support Others</h3>
                            <p class="text-sm text-gray-400">Daily presence</p>
                        </div>
                    </div>
                    <p class="text-gray-200 mb-4">
                        Help others cope, share wisdom, be present. Consistent supportive members earn consistent recognition.
                    </p>
                    <div class="text-sm text-purple-300">🤝 Consistency pays</div>
                </div>

                <div class="glass p-8 rounded-2xl hover:scale-105 transition transform">
                    <div class="flex items-center mb-4">
                        <div class="text-5xl mr-4">🤖</div>
                        <div>
                            <h3 class="text-2xl font-bold text-purple-300">Use AI Tools</h3>
                            <p class="text-sm text-gray-400">Bot interaction</p>
                        </div>
                    </div>
                    <p class="text-gray-200 mb-4">
                        Use SASA AI for analysis and memes. Active users earn small consistent rewards for engagement.
                    </p>
                    <div class="text-sm text-purple-300">🔄 Passive earning</div>
                </div>

                <div class="glass p-8 rounded-2xl hover:scale-105 transition transform">
                    <div class="flex items-center mb-4">
                        <div class="text-5xl mr-4">🏆</div>
                        <div>
                            <h3 class="text-2xl font-bold text-purple-300">Compete</h3>
                            <p class="text-sm text-gray-400">Contests & events</p>
                        </div>
                    </div>
                    <p class="text-gray-200 mb-4">
                        Join weekly/monthly contests. Winners receive significant bonus rewards and community recognition.
                    </p>
                    <div class="text-sm text-purple-300">🎯 Skill-based</div>
                </div>

                <div class="glass p-8 rounded-2xl hover:scale-105 transition transform">
                    <div class="flex items-center mb-4">
                        <div class="text-5xl mr-4">💎</div>
                        <div>
                            <h3 class="text-2xl font-bold text-purple-300">Hold & Believe</h3>
                            <p class="text-sm text-gray-400">Long-term</p>
                        </div>
                    </div>
                    <p class="text-gray-200 mb-4">
                        Active long-term holders receive surprise airdrops and benefits. Early believers may benefit most.
                    </p>
                    <div class="text-sm text-purple-300">⏳ Patience rewarded</div>
                </div>

            </div>

            <div class="mt-12 text-center">
                <div class="glass p-8 rounded-2xl max-w-3xl mx-auto">
                    <h3 class="text-3xl font-bold mb-4">💡 Fair Reward Distribution</h3>
                    <p class="text-xl text-gray-300 mb-6">
                        50% of tokens go to community rewards, distributed algorithmically based on verified contributions. No fixed amounts — your impact determines your rewards.
                    </p>
                    <div class="grid grid-cols-3 gap-4 text-center">
                        <div>
                            <div class="text-3xl font-bold text-purple-400">50%</div>
                            <div class="text-sm text-gray-400">Community Pool</div>
                        </div>
                        <div>
                            <div class="text-3xl font-bold text-pink-400">30%</div>
                            <div class="text-sm text-gray-400">Contests & Events</div>
                        </div>
                        <div>
                            <div class="text-3xl font-bold text-yellow-400">20%</div>
                            <div class="text-sm text-gray-400">Development</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Tier System -->
    <section id="tiers" class="py-20 bg-gray-900">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-5xl font-bold text-center mb-6">Recognition <span class="gradient-text">Tiers</span></h2>
            <p class="text-xl text-gray-300 text-center mb-16 max-w-3xl mx-auto">
                Progress through tiers by contributing authentically. Higher tiers unlock better benefits and larger reward pools. All tiers receive support. 💜
            </p>

            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
                
                <!-- Bronze -->
                <div class="tier-card p-6 rounded-xl">
                    <div class="text-5xl mb-3 text-center">🥉</div>
                    <h3 class="text-2xl font-bold text-center mb-3 text-orange-400">BRONZE</h3>
                    <p class="text-center text-gray-400 text-sm mb-4">New Members</p>
                    <ul class="space-y-2 text-sm text-gray-300">
                        <li>✓ Share verified stories</li>
                        <li>✓ Access to community</li>
                        <li>✓ Small token rewards</li>
                        <li>✓ Learning resources</li>
                        <li>✓ Basic bot access</li>
                    </ul>
                    <div class="mt-4 pt-4 border-t border-gray-700">
                        <p class="text-xs text-center text-gray-400">Unlock: Immediate</p>
                    </div>
                </div>

                <!-- Silver -->
                <div class="tier-card p-6 rounded-xl">
                    <div class="text-5xl mb-3 text-center">🥈</div>
                    <h3 class="text-2xl font-bold text-center mb-3 text-gray-300">SILVER</h3>
                    <p class="text-center text-gray-400 text-sm mb-4">Active Members</p>
                    <ul class="space-y-2 text-sm text-gray-300">
                        <li>✓ Regular rewards</li>
                        <li>✓ Featured content</li>
                        <li>✓ Priority bot access</li>
                        <li>✓ Contest eligibility</li>
                        <li>✓ Verified badge</li>
                    </ul>
                    <div class="mt-4 pt-4 border-t border-gray-700">
                        <p class="text-xs text-center text-gray-400">Unlock: 5 verified stories</p>
                    </div>
                </div>

                <!-- Gold -->
                <div class="tier-card p-6 rounded-xl border-yellow-400">
                    <div class="text-5xl mb-3 text-center">🥇</div>
                    <h3 class="text-2xl font-bold text-center mb-3 text-yellow-400">GOLD</h3>
                    <p class="text-center text-gray-400 text-sm mb-4">Top Contributors</p>
                    <ul class="space-y-2 text-sm text-gray-300">
                        <li>✓ Substantial rewards</li>
                        <li>✓ Community influence</li>
                        <li>✓ Exclusive perks</li>
                        <li>✓ Moderation powers</li>
                        <li>✓ Monthly bonuses</li>
                    </ul>
                    <div class="mt-4 pt-4 border-t border-gray-700">
                        <p class="text-xs text-center text-gray-400">Unlock: Consistent quality</p>
                    </div>
                </div>

                <!-- Diamond -->
                <div class="tier-card p-6 rounded-xl border-cyan-400">
                    <div class="text-5xl mb-3 text-center">💎</div>
                    <h3 class="text-2xl font-bold text-center mb-3 text-cyan-400">DIAMOND</h3>
                    <p class="text-center text-gray-400 text-sm mb-4">Legends</p>
                    <ul class="space-y-2 text-sm text-gray-300">
                        <li>✓ Maximum rewards</li>
                        <li>✓ Governance rights</li>
                        <li>✓ Lifetime benefits</li>
                        <li>✓ Hall of Fame</li>
                        <li>✓ Legacy status</li>
                    </ul>
                    <div class="mt-4 pt-4 border-t border-gray-700">
                        <p class="text-xs text-center text-gray-400">Unlock: Exceptional impact</p>
                    </div>
                </div>

            </div>

            <div class="mt-12 glass p-6 rounded-xl max-w-3xl mx-auto text-center">
                <p class="text-lg text-gray-300">
                    <strong class="text-purple-300">Progression is natural.</strong> Focus on contributing authentically, helping others, and building community. Recognition and rewards follow naturally. 🌟
                </p>
            </div>
        </div>
    </section>

    <!-- Realistic Expectations -->
    <section class="py-20 bg-gray-800">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-5xl font-bold text-center mb-12">Realistic <span class="gradient-text">Expectations</span></h2>
            
            <div class="grid md:grid-cols-2 gap-8 mb-12">
                
                <div class="glass p-8 rounded-xl">
                    <h3 class="text-3xl font-bold mb-6 text-green-400 flex items-center">
                        <span class="mr-3">✅</span> What IS Realistic
                    </h3>
                    <ul class="space-y-4 text-lg text-gray-300">
                        <li class="flex items-start">
                            <span class="text-green-400 mr-3">→</span>
                            <span>Small rewards for casual participation</span>
                        </li>
                        <li class="flex items-start">
                            <span class="text-green-400 mr-3">→</span>
                            <span>Growing rewards for consistent effort</span>
                        </li>
                        <li class="flex items-start">
                            <span class="text-green-400 mr-3">→</span>
                            <span>Significant rewards for major contributions</span>
                        </li>
                        <li class="flex items-start">
                            <span class="text-green-400 mr-3">→</span>
                            <span>Genuine community support (priceless)</span>
                        </li>
                        <li class="flex items-start">
                            <span class="text-green-400 mr-3">→</span>
                            <span>Early believers may profit significantly</span>
                        </li>
                        <li class="flex items-start">
                            <span class="text-green-400 mr-3">→</span>
                            <span>Transparent, fair reward distribution</span>
                        </li>
                    </ul>
                </div>

            </div>

            <div class="glass p-8 rounded-xl max-w-4xl mx-auto">
                <h3 class="text-3xl font-bold mb-6 text-center gradient-text">The Honest Truth</h3>
                <div class="space-y-4 text-lg text-gray-300">
                    <p>
                        <strong class="text-purple-300">If you're here just to cope:</strong> You'll get support, community, and understanding. That's valuable and always free. 💜
                    </p>
                    <p>
                        <strong class="text-purple-300">If you're here to contribute:</strong> You'll earn tokens as recognition. How much? Depends on your impact and the community's growth. 🤝
                    </p>
                    <p>
                        <strong class="text-purple-300">If you believe early and stay active:</strong> You might profit significantly... or you might not. That's crypto. But you'll definitely be part of something real. 🚀
                    </p>
                    <p class="text-center pt-4 text-xl font-semibold text-purple-200">
                        No promises. Just honesty. That's the SASA way.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Verification System -->
    <section class="py-20 bg-gray-900">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-5xl font-bold text-center mb-6">How We Ensure <span class="gradient-text">Authenticity</span></h2>
            <p class="text-xl text-gray-300 text-center mb-16 max-w-3xl mx-auto">
                Every submission is verified. Fake stories = no rewards. We value genuine experiences and build trust through transparency. 🔍
            </p>

            <div class="grid md:grid-cols-3 gap-8">
                
                <div class="glass p-8 rounded-xl">
                    <div class="text-6xl mb-4 text-center">📸</div>
                    <h3 class="text-2xl font-bold mb-4 text-center text-purple-300">Proof Required</h3>
                    <ul class="space-y-3 text-gray-300">
                        <li>• Transaction hash verification</li>
                        <li>• Screenshot requirements</li>
                        <li>• On-chain data check</li>
                        <li>• Privacy-respecting (can blur wallet)</li>
                        <li>• Auto-rejection of fakes</li>
                    </ul>
                </div>

                <div class="glass p-8 rounded-xl">
                    <div class="text-6xl mb-4 text-center">🗳️</div>
                    <h3 class="text-2xl font-bold mb-4 text-center text-purple-300">Community Vote</h3>
                    <ul class="space-y-3 text-gray-300">
                        <li>• Members vote on stories</li>
                        <li>• Quality determines rewards</li>
                        <li>• Authenticity matters</li>
                        <li>• Popular stories featured</li>
                        <li>• Democratic distribution</li>
                    </ul>
                </div>

                <div class="glass p-8 rounded-xl">
                    <div class="text-6xl mb-4 text-center">🛡️</div>
                    <h3 class="text-2xl font-bold mb-4 text-center text-purple-300">Reputation System</h3>
                    <ul class="space-y-3 text-gray-300">
                        <li>• Build trust over time</li>
                        <li>• Tier progression tracking</li>
                        <li>• Fake attempts = warnings</li>
                        <li>• 3 strikes = ban</li>
                        <li>• Honest members rewarded</li>
                    </ul>
                </div>

            </div>

            <div class="mt-12 text-center glass p-6 rounded-xl max-w-3xl mx-auto">
                <p class="text-lg text-gray-300">
                    <strong class="text-purple-300">We take authenticity seriously.</strong> Every verified member makes the community stronger. Every fake attempt weakens trust. We protect what we're building together. 🔒
                </p>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="py-20 bg-gray-800">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-5xl font-bold text-center mb-16">Community Features</h2>
            <div class="grid md:grid-cols-3 gap-8">
                
                <div class="glass p-8 rounded-2xl hover:scale-105 transition transform">
                    <div class="text-6xl mb-4">😂</div>
                    <h3 class="text-2xl font-bold mb-4">AI Meme Generator</h3>
                    <p class="text-gray-300">
                        SASA AI creates personalized consolation memes. Turn your pain into laughs, share with the community, earn recognition.
                    </p>
                </div>

                <div class="glass p-8 rounded-2xl hover:scale-105 transition transform">
                    <div class="text-6xl mb-4">📊</div>
                    <h3 class="text-2xl font-bold mb-4">Loss Analytics</h3>
                    <p class="text-gray-300">
                        Submit trades for AI analysis with dark humor. Learn from mistakes while earning tokens for sharing insights.
                    </p>
                </div>

                <div class="glass p-8 rounded-2xl hover:scale-105 transition transform">
                    <div class="text-6xl mb-4">🏆</div>
                    <h3 class="text-2xl font-bold mb-4">Hall of Fame</h3>
                    <p class="text-gray-300">
                        Monthly recognition for top contributors. Your legacy lives on. Become a SASA legend.
                    </p>
                </div>

                <div class="glass p-8 rounded-2xl hover:scale-105 transition transform">
                    <div class="text-6xl mb-4">💬</div>
                    <h3 class="text-2xl font-bold mb-4">24/7 Support</h3>
                    <p class="text-gray-300">
                        Community never sleeps. Someone's always there to help. Free support, always.
                    </p>
                </div>

                <div class="glass p-8 rounded-2xl hover:scale-105 transition transform">
                    <div class="text-6xl mb-4">🎯</div>
                    <h3 class="text-2xl font-bold mb-4">Cope Score™</h3>
                    <p class="text-gray-300">
                        Track your journey. Calculate your resilience. Higher scores = respect + bonus opportunities.
                    </p>
                </div>

                <div class="glass p-8 rounded-2xl hover:scale-105 transition transform">
                    <div class="text-6xl mb-4">🎁</div>
                    <h3 class="text-2xl font-bold mb-4">Surprise Airdrops</h3>
                    <p class="text-gray-300">
                        Active members receive unexpected rewards. Stay engaged, stay rewarded.
                    </p>
                </div>

            </div>
        </div>
    </section>

    <!-- How to Buy -->
    <section id="how" class="py-20 bg-gray-900">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-5xl font-bold text-center mb-16">How to Join $SASA</h2>
            <div class="grid md:grid-cols-4 gap-8">
                
                <div class="text-center">
                    <div class="w-20 h-20 bg-gradient-to-br from-purple-600 to-pink-600 rounded-full flex items-center justify-center text-3xl font-bold mx-auto mb-4 pulse">1</div>
                    <h3 class="text-xl font-bold mb-2">Get a Wallet</h3>
                    <p class="text-gray-400">Download Phantom or Solflare for Solana</p>
                </div>

                <div class="text-center">
                    <div class="w-20 h-20 bg-gradient-to-br from-purple-600 to-pink-600 rounded-full flex items-center justify-center text-3xl font-bold mx-auto mb-4 pulse" style="animation-delay: 0.2s;">2</div>
                    <h3 class="text-xl font-bold mb-2">Buy SOL</h3>
                    <p class="text-gray-400">Purchase SOL and send to your wallet</p>
                </div>

                <div class="text-center">
                    <div class="w-20 h-20 bg-gradient-to-br from-purple-600 to-pink-600 rounded-full flex items-center justify-center text-3xl font-bold mx-auto mb-4 pulse" style="animation-delay: 0.4s;">3</div>
                    <h3 class="text-xl font-bold mb-2">Go to Pump.fun</h3>
                    <p class="text-gray-400">Find $SASA and connect wallet</p>
                </div>

                <div class="text-center">
                    <div class="w-20 h-20 bg-gradient-to-br from-purple-600 to-pink-600 rounded-full flex items-center justify-center text-3xl font-bold mx-auto mb-4 pulse" style="animation-delay: 0.6s;">4</div>
                    <h3 class="text-xl font-bold mb-2">Swap for $SASA</h3>
                    <p class="text-gray-400">Join the community!</p>
                </div>

            </div>

            <div class="mt-12 text-center">
                <button class="bg-gradient-to-r from-purple-600 via-pink-500 to-purple-600 px-12 py-4 rounded-full font-bold text-xl hover:scale-105 transition transform shadow-lg">
                    Buy on Pump.fun →
                </button>
                <p class="mt-6 text-gray-400">Early members unlock exclusive benefits 🎁</p>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="py-20 bg-gray-800">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-5xl font-bold text-center mb-16">Real Stories</h2>
            <div class="grid md:grid-cols-3 gap-8">
                
                <div class="bg-gray-900 p-6 rounded-xl border-l-4 border-purple-400">
                    <p class="text-lg mb-4">"Lost money, found community. The tokens are nice, but the support is what kept me here. SASA is real." 💜</p>
                    <p class="text-gray-400 text-sm">- Early Member</p>
                </div>

                <div class="bg-gray-900 p-6 rounded-xl border-l-4 border-pink-400">
                    <p class="text-lg mb-4">"No BS promises. Just honest people helping each other. That's rare in crypto. Been here 3 months, no regrets." 🤝</p>
                    <p class="text-gray-400 text-sm">- Active Contributor</p>
                </div>

                <div class="bg-gray-900 p-6 rounded-xl border-l-4 border-yellow-400">
                    <p class="text-lg mb-4">"Started for the memes. Stayed for the community. Now I'm a Gold tier. Rewards are fair, people are genuine." ✨</p>
                    <p class="text-gray-400 text-sm">- Gold Member</p>
                </div>

            </div>
        </div>
    </section>

    <!-- Community -->
    <section class="py-20 bg-gray-900">
        <div class="max-w-6xl mx-auto px-4 text-center">
            <h2 class="text-5xl font-bold mb-8">Join the SASA Family</h2>
            <p class="text-xl text-gray-300 mb-12 max-w-3xl mx-auto">
                Thousands of traders supporting each other daily. No hype. No BS. Just real people building something honest together. 💜
            </p>
            <div class="flex flex-wrap justify-center gap-6">
                <a href="#" class="glass px-8 py-4 rounded-full font-bold text-lg hover:scale-105 transition transform flex items-center gap-2">
                    <span>💬</span> Telegram
                </a>
                <a href="#" class="glass px-8 py-4 rounded-full font-bold text-lg hover:scale-105 transition transform flex items-center gap-2">
                    <span>🐦</span> Twitter/X
                </a>
                <a href="#" class="glass px-8 py-4 rounded-full font-bold text-lg hover:scale-105 transition transform flex items-center gap-2">
                    <span>📊</span> Chart
                </a>
            </div>
        </div>
    </section>

    <!-- FAQ -->
    <section class="py-20 bg-gray-800">
        <div class="max-w-4xl mx-auto px-4">
            <h2 class="text-5xl font-bold text-center mb-16">Common Questions</h2>
            <div class="space-y-6">
                
                <div class="glass p-6 rounded-xl">
                    <h3 class="text-xl font-bold mb-3 text-purple-400">💰 How much can I actually earn?</h3>
                    <p class="text-gray-300">It varies based on your contribution quality, consistency, and community growth. We don't promise fixed amounts because that would be dishonest. Casual members earn small rewards. Active contributors earn more. Legends earn significantly more. All amounts are transparent and fair.</p>
                </div>

                <div class="glass p-6 rounded-xl">
                    <h3 class="text-xl font-bold mb-3 text-purple-400">🤔 Why should I trust SASA?</h3>
                    <p class="text-gray-300">We don't make unrealistic promises. We verify all submissions. We distribute rewards transparently. We prioritize community over hype. Judge us by our actions, not our words. Start small, see for yourself.</p>
                </div>

                <div class="glass p-6 rounded-xl">
                    <h3 class="text-xl font-bold mb-3 text-purple-400">📸 What proof do I need for loss stories?</h3>
                    <p class="text-gray-300">Transaction hash, screenshot showing the trade, and a brief story. We verify on-chain. You can blur your wallet address for privacy. Fake submissions are rejected and tracked.</p>
                </div>

                <div class="glass p-6 rounded-xl">
                    <h3 class="text-xl font-bold mb-3 text-purple-400">🚀 What's the long-term vision?</h3>
                    <p class="text-gray-300">Build the most supportive trading community in crypto. Develop advanced AI tools. Create sustainable reward economy. Partner with mental health resources. Launch NFT collection. Help traders cope while building something valuable together.</p>
                </div>

                <div class="glass p-6 rounded-xl">
                    <h3 class="text-xl font-bold mb-3 text-purple-400">⚠️ What are the risks?</h3>
                    <p class="text-gray-300">Token value can go down (or to zero). Rewards might not cover your losses. Community might not grow as expected. These are real risks. We're honest about them. Only invest what you can afford to lose. Come for community first, potential profits second.</p>
                </div>

            </div>
        </div>
    </section>

    <!-- Final CTA -->
    <section class="gradient-bg py-20">
        <div class="max-w-4xl mx-auto px-4 text-center">
            <h2 class="text-5xl md:text-6xl font-bold mb-6">Ready to Cope Together?</h2>
            <p class="text-2xl mb-8 opacity-90">
                Join the honest crypto community where support is free and contributions are rewarded fairly.
            </p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center mb-8">
                <button class="bg-white text-purple-600 px-12 py-5 rounded-full font-bold text-xl hover:scale-105 transition transform shadow-2xl">
                    Join Community 🤝
                </button>
                <button class="glass px-12 py-5 rounded-full font-bold text-xl hover:scale-105 transition transform">
                    Buy $SASA
                </button>
            </div>
            <p class="text-sm opacity-75">No promises. Just honesty. That's the SASA difference. 💜</p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 py-12 border-t border-gray-800">
        <div class="max-w-6xl mx-auto px-4">
            <div class="text-center mb-8">
                <svg viewBox="0 0 500 500" xmlns="http://www.w3.org/2000/svg" class="w-32 h-32 mx-auto mb-4">
                    <g>
                        <rect x="150" y="180" width="200" height="180" rx="30" fill="#a8b3ff" stroke="#fff" stroke-width="4"/>
                        <line x1="250" y1="180" x2="250" y2="140" stroke="#fff" stroke-width="6" stroke-linecap="round"/>
                        <circle cx="250" cy="135" r="12" fill="#ff6b9d"/>
                        <ellipse cx="200" cy="240" rx="25" ry="30" fill="#fff"/>
                        <ellipse cx="205" cy="245" rx="12" ry="15" fill="#4a5568"/>
                        <path d="M 180 225 Q 200 215 220 225" stroke="#8b9cff" stroke-width="3" fill="none" stroke-linecap="round"/>
                        <ellipse cx="300" cy="240" rx="25" ry="30" fill="#fff"/>
                        <ellipse cx="295" cy="245" rx="12" ry="15" fill="#4a5568"/>
                        <path d="M 280 225 Q 300 215 320 225" stroke="#8b9cff" stroke-width="3" fill="none" stroke-linecap="round"/>
                        <ellipse cx="195" cy="270" rx="6" ry="12" fill="#64b5f6" opacity="0.7"/>
                        <ellipse cx="195" cy="285" rx="5" ry="8" fill="#64b5f6" opacity="0.7"/>
                        <ellipse cx="305" cy="275" rx="6" ry="12" fill="#64b5f6" opacity="0.7"/>
                        <path d="M 200 310 Q 250 290 300 310" stroke="#fff" stroke-width="6" fill="none" stroke-linecap="round"/>
                        <ellipse cx="130" cy="280" rx="20" ry="15" fill="#ff6b9d" opacity="0.4"/>
                        <ellipse cx="370" cy="280" rx="20" ry="15" fill="#ff6b9d" opacity="0.4"/>
                    </g>
                </svg>
                <h3 class="text-3xl font-bold mb-2">SASA</h3>
                <p class="text-lg opacity-75 mb-6 gradient-text font-semibold">Cope Together, Earn Together</p>
                
                <div class="flex justify-center space-x-6 mb-8">
                    <a href="#" class="text-gray-400 hover:text-white transition">Twitter</a>
                    <a href="#" class="text-gray-400 hover:text-white transition">Telegram</a>
                    <a href="#" class="text-gray-400 hover:text-white transition">Discord</a>
                    <a href="#" class="text-gray-400 hover:text-white transition">Chart</a>
                </div>
            </div>
            
            <div class="border-t border-gray-800 pt-8 text-center">
                <p class="text-sm text-gray-400 mb-4">
                    <strong>Disclaimer:</strong> $SASA is a community token with no guaranteed financial returns. 
                    Crypto investments are risky. Rewards vary based on contribution and community growth. 
                    Only invest what you can afford to lose. Support is free, tokens are a bonus. DYOR. Not financial advice.
                </p>
                <p class="text-sm text-gray-500">
                    © 2025 SASA Token. Built with honesty and 💜 by traders, for traders.
                </p>
                <p class="text-xs text-gray-600 mt-2">
                    No promises. Just real community. That's our commitment. 🤝
                </p>
            </div>
        </div>
    </footer>

    <script>
        // Smooth scroll
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({ behavior: 'smooth', block: 'start' });
                }
            });
        });

        // Scroll animations
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, observerOptions);

        document.querySelectorAll('.fade-in-up').forEach(el => {
            el.style.opacity = '0';
            el.style.transform = 'translateY(30px)';
            el.style.transition = 'all 0.8s ease-out';
            observer.observe(el);
        });
    </script>

</body>
</html>

                <div class="glass p-8 rounded-xl">
                    <h3 class="text-3xl font-bold mb-6 text-red-400 flex items-center">
                        <span class="mr-3">❌</span> What is NOT Realistic
                    </h3>
                    <ul class="space-y-4 text-lg text-gray-300">
                        <li class="flex items-start">
                            <span class="text-red-400 mr-3">→</span>
                            <span>Get rich quick schemes</span>
                        </li>
                        <li class="flex items-start">
                            <span class="text-red-400 mr-3">→</span>
                            <span>Guaranteed income or recovery of losses</span>
                        </li>
                        <li class="flex items-start">
                            <span class="text-red-400 mr-3">→</span>
                            <span>Zero effort = big rewards</span>
                        </li>
                        <li class="flex items-start">
                            <span class="text-red-400 mr-3">→</span>
                            <span>Fixed promised amounts</span>
                        </li>
                        <li class="flex items-start">
                            <span class="text-red-400 mr-3">→</span>
                            <span>No risk investing</span>
                        </li>
                        <li class="flex items-start">
                            <span class="text-red-400 mr-3">→</span>
                            <span>Everyone becomes profitable</span>
                        </li>
                    </ul>
