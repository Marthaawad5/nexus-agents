import React from 'react';

export default function Home() {
  return (
    <html lang="en" className="h-full antialiased scroll-smooth">
      <head>
        <meta charSet="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Vexa • Digital Agents</title>
        <link rel="preconnect" href="https://fonts.googleapis.com" />
        <link rel="preconnect" href="https://fonts.gstatic.com" crossOrigin="" />
        <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />
        <script src="https://cdn.tailwindcss.com"></script>
        <script src="https://unpkg.com/lucide@latest"></script>
        <style>
          {`
          body{font-family:'Inter',sans-serif;}
          .animate-fade-in { animation: fadeIn 0.8s ease-out forwards; opacity: 0; }
          .animate-slide-up { animation: slideUp 0.8s ease-out forwards; opacity: 0; transform: translateY(20px); }
          .animate-slide-left { animation: slideLeft 0.8s ease-out forwards; opacity: 0; transform: translateX(20px); }
          @keyframes fadeIn { to { opacity: 1; } }
          @keyframes slideUp { to { opacity: 1; transform: translateY(0); } }
          @keyframes slideLeft { to { opacity: 1; transform: translateX(0); } }
          .delay-100 { animation-delay: 100ms; }
          .delay-200 { animation-delay: 200ms; }
          .delay-300 { animation-delay: 300ms; }
          .delay-400 { animation-delay: 400ms; }
          .delay-500 { animation-delay: 500ms; }
          .delay-600 { animation-delay: 600ms; }
          .delay-700 { animation-delay: 700ms; }
          .delay-800 { animation-delay: 800ms; }
          `}
        </style>
        <link id="all-fonts-link-font-geist" rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Geist:wght@300;400;500;600;700&display=swap" />
        <style id="all-fonts-style-font-geist">{`.font-geist { font-family: 'Geist', sans-serif !important; }`}</style>
        <link id="all-fonts-link-font-roboto" rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;600;700&display=swap" />
        <style id="all-fonts-style-font-roboto">{`.font-roboto { font-family: 'Roboto', sans-serif !important; }`}</style>
        <link id="all-fonts-link-font-montserrat" rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700&display=swap" />
        <style id="all-fonts-style-font-montserrat">{`.font-montserrat { font-family: 'Montserrat', sans-serif !important; }`}</style>
        <link id="all-fonts-link-font-poppins" rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" />
        <style id="all-fonts-style-font-poppins">{`.font-poppins { font-family: 'Poppins', sans-serif !important; }`}</style>
        <link id="all-fonts-link-font-playfair" rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700;900&display=swap" />
        <style id="all-fonts-style-font-playfair">{`.font-playfair { font-family: 'Playfair Display', serif !important; }`}</style>
        <link id="all-fonts-link-font-instrument-serif" rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Instrument+Serif:wght@400;500;600;700&display=swap" />
        <style id="all-fonts-style-font-instrument-serif">{`.font-instrument-serif { font-family: 'Instrument Serif', serif !important; }`}</style>
        <link id="all-fonts-link-font-merriweather" rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Merriweather:wght@300;400;700;900&display=swap" />
        <style id="all-fonts-style-font-merriweather">{`.font-merriweather { font-family: 'Merriweather', serif !important; }`}</style>
        <link id="all-fonts-link-font-bricolage" rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@300;400;500;600;700&display=swap" />
        <style id="all-fonts-style-font-bricolage">{`.font-bricolage { font-family: 'Bricolage Grotesque', sans-serif !important; }`}</style>
        <link id="all-fonts-link-font-jakarta" rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" />
        <style id="all-fonts-style-font-jakarta">{`.font-jakarta { font-family: 'Plus Jakarta Sans', sans-serif !important; }`}</style>
        <link id="all-fonts-link-font-manrope" rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Manrope:wght@300;400;500;600;700;800&display=swap" />
        <style id="all-fonts-style-font-manrope">{`.font-manrope { font-family: 'Manrope', sans-serif !important; }`}</style>
        <link id="all-fonts-link-font-space-grotesk" rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700&display=swap" />
        <style id="all-fonts-style-font-space-grotesk">{`.font-space-grotesk { font-family: 'Space Grotesk', sans-serif !important; }`}</style>
        <link id="all-fonts-link-font-work-sans" rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Work+Sans:wght@300;400;500;600;700;800&display=swap" />
        <style id="all-fonts-style-font-work-sans">{`.font-work-sans { font-family: 'Work Sans', sans-serif !important; }`}</style>
        <link id="all-fonts-link-font-pt-serif" rel="stylesheet" href="https://fonts.googleapis.com/css2?family=PT+Serif:wght@400;700&display=swap" />
        <style id="all-fonts-style-font-pt-serif">{`.font-pt-serif { font-family: 'PT Serif', serif !important; }`}</style>
        <link id="all-fonts-link-font-geist-mono" rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Geist+Mono:wght@300;400;500;600;700&display=swap" />
        <style id="all-fonts-style-font-geist-mono">{`.font-geist-mono { font-family: 'Geist Mono', monospace !important; }`}</style>
        <link id="all-fonts-link-font-space-mono" rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&display=swap" />
        <style id="all-fonts-style-font-space-mono">{`.font-space-mono { font-family: 'Space Mono', monospace !important; }`}</style>
        <link id="all-fonts-link-font-quicksand" rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;500;600;700&display=swap" />
        <style id="all-fonts-style-font-quicksand">{`.font-quicksand { font-family: 'Quicksand', sans-serif !important; }`}</style>
        <link id="all-fonts-link-font-nunito" rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Nunito:wght@300;400;500;600;700;800&display=swap" />
        <style id="all-fonts-style-font-nunito">{`.font-nunito { font-family: 'Nunito', sans-serif !important; }`}</style>
      </head>
      <body className="min-h-screen">
        {/* Page Wrapper */}
        <div className="min-h-screen w-full flex flex-col lg:flex-row relative max-w-7xl bg-white mt-8 mr-auto mb-8 ml-auto shadow-2xl rounded-3xl overflow-hidden">
          
          {/* Left Column */}
          <div className="w-full lg:w-1/2 sm:p-6 md:p-8 lg:p-12 flex flex-col pt-4 pr-4 pb-4 pl-4">
            {/* Top Bar */}
            <div className="flex items-center justify-between mb-8 lg:mb-12 animate-fade-in">
              <div className="flex gap-2 items-center">
                <span className="text-xl font-semibold tracking-tight font-geist">VEXA</span>
              </div>

              <nav className="hidden md:flex space-x-6 text-sm font-medium">
                <a href="#" className="hover:text-gray-900 tracking-wider transition-colors duration-200 flex items-center gap-1 font-geist">
                  <i data-lucide="compass" className="w-4 h-4"></i>
                  EXPLORE
                </a>
                <a href="#" className="hover:text-gray-900 tracking-wider transition-colors duration-200 flex items-center gap-1 font-geist">
                  <i data-lucide="credit-card" className="w-4 h-4"></i>
                  PRICING
                </a>
                <a href="#" className="hover:text-gray-900 tracking-wider transition-colors duration-200 flex items-center gap-1 font-geist">
                  <i data-lucide="code" className="w-4 h-4"></i>
                  API
                </a>
              </nav>

              <button className="flex gap-2 hover:bg-gray-900 transition-all duration-200 hover:scale-105 text-xs font-medium text-white font-geist bg-black rounded-lg pt-2 pr-4 pb-2 pl-4 shadow-[0_2.8px_2.2px_rgba(0,_0,_0,_0.034),_0_6.7px_5.3px_rgba(0,_0,_0,_0.048),_0_12.5px_10px_rgba(0,_0,_0,_0.06),_0_22.3px_17.9px_rgba(0,_0,_0,_0.072),_0_41.8px_33.4px_rgba(0,_0,_0,_0.086),_0_100px_80px_rgba(0,_0,_0,_0.12)] items-center">
                <i data-lucide="smartphone" className="w-4 h-4"></i>
                GET THE APP
              </button>
            </div>

            {/* Hero Copy */}
            <div className="flex-1 flex flex-col justify-center">
              <div className="lg:space-y-8 space-y-6">
                <div className="animate-fade-in delay-100 flex gap-2 text-sm font-medium text-gray-700 tracking-widest items-center font-geist">
                  NEW LAUNCH
                  <i data-lucide="terminal" className="w-4 h-4"></i>
                </div>
                <h1 className="sm:text-4xl md:text-5xl lg:text-6xl leading-tight animate-slide-up delay-200 text-3xl font-semibold tracking-tight font-space-grotesk">
                  CRAFTING 
                  HUMAN-LIKE 
                  DIGITAL AGENTS 
                  <span className="text-transparent bg-clip-text bg-gradient-to-r from-gray-900 to-gray-600 font-space-grotesk font-semibold">WITH PURPOSE</span>
                </h1>
                <p className="max-w-md text-sm tracking-wide leading-relaxed text-gray-600 animate-slide-up delay-300 font-geist">
                  Discover revolutionary AI-powered tools to build, deploy, and scale autonomous digital agents across web systems. Transform your workflow with intelligent automation that learns and adapts.
                </p>

                <div className="flex flex-col sm:flex-row gap-4 animate-slide-up delay-400">
                  <button className="inline-flex gap-2 self-start hover:border-gray-900 transition-all duration-200 hover:shadow-md hover:scale-105 text-sm font-medium border-gray-400 border rounded-xl pt-3 pr-6 pb-3 pl-6 shadow-[0_2.8px_2.2px_rgba(0,_0,_0,_0.034),_0_6.7px_5.3px_rgba(0,_0,_0,_0.048),_0_12.5px_10px_rgba(0,_0,_0,_0.06),_0_22.3px_17.9px_rgba(0,_0,_0,_0.072),_0_41.8px_33.4px_rgba(0,_0,_0,_0.086),_0_100px_80px_rgba(0,_0,_0,_0.12)] items-center">
                    <i data-lucide="rocket" className="w-4 h-4"></i>
                    <span className="tracking-wider font-geist">DEPLOY AGENT</span>
                  </button>
                  <button className="inline-flex items-center gap-2 self-start text-sm font-medium px-6 py-3 rounded-xl text-gray-700 hover:text-gray-900 transition-colors duration-200">
                    <i data-lucide="play-circle" className="w-4 h-4"></i>
                    <span className="tracking-wider font-geist">WATCH DEMO</span>
                  </button>
                </div>

                {/* Stats */}
                <div className="flex items-center gap-8 pt-6 animate-fade-in delay-500">
                  <div className="text-center">
                    <div className="text-2xl text-gray-900 font-space-grotesk font-semibold">2.5M+</div>
                    <div className="text-xs text-gray-600 tracking-wider font-geist">AGENTS DEPLOYED</div>
                  </div>
                  <div className="text-center">
                    <div className="text-2xl text-gray-900 font-space-grotesk font-semibold">99.9%</div>
                    <div className="text-xs text-gray-600 tracking-wider font-geist">UPTIME</div>
                  </div>
                  <div className="text-center">
                    <div className="text-2xl text-gray-900 font-space-grotesk font-semibold">&lt; 50ms</div>
                    <div className="text-xs text-gray-600 tracking-wider font-geist">RESPONSE TIME</div>
                  </div>
                </div>
              </div>

              {/* Modules */}
              <div className="mt-12 grid grid-cols-1 sm:grid-cols-2 gap-4 max-w-lg animate-slide-up delay-600">
                {/* Core Module Card */}
                <div className="relative h-48 sm:h-56 overflow-hidden flex group cursor-pointer hover:scale-105 transition-all duration-300 bg-[url(https://cdn.midjourney.com/1741ccc5-3df1-471e-9e41-b528ea13c963/0_0.png?w=800&q=80)] bg-cover rounded-xl items-center justify-center">
                  <div className="absolute top-3 left-3 text-[10px] tracking-widest text-white/70 flex items-center gap-1 font-geist">
                    <i data-lucide="cpu" className="w-3 h-3"></i>
                    CORE MODULE
                  </div>
                  <i data-lucide="atom" className="w-16 h-16 text-white group-hover:scale-110 transition-transform duration-300"></i>
                  <div className="absolute bottom-3 left-3 right-3">
                    <div className="text-xs text-white/90 font-medium font-geist">Neural Processing Unit</div>
                    <div className="text-[10px] text-white/70 font-geist">Advanced AI reasoning core</div>
                  </div>
                  <i data-lucide="arrow-up-right" className="absolute top-3 right-3 w-4 h-4 text-white/80 group-hover:text-white transition-colors duration-300"></i>
                </div>
                
                {/* Agent Skin Card */}
                <div className="relative h-48 sm:h-56 bg-gray-100 rounded-xl overflow-hidden group cursor-pointer hover:scale-105 transition-all duration-300">
                  <div className="absolute top-3 left-3 text-[10px] tracking-widest text-gray-700 flex items-center gap-1 z-10 font-geist">
                    <i data-lucide="user" className="w-3 h-3"></i>
                    AGENT SKIN
                  </div>
                  <img src="https://cdn.midjourney.com/4ac09c6f-b2a4-42ae-b133-70257fe250fe/0_0.png?w=800&q=80" alt="Agent Skin" className="w-full h-full object-cover group-hover:scale-110 transition-transform duration-300" />
                  <div className="absolute inset-0 group-hover:bg-black/30 transition-colors duration-300 bg-black/20"></div>
                  <div className="absolute bottom-3 left-3 right-3 z-10">
                    <div className="text-xs text-white font-medium font-geist">Marcus Chen</div>
                    <div className="text-[10px] text-white/80 font-geist">Customer Success Agent</div>
                  </div>
                  <i data-lucide="arrow-up-right" className="absolute top-3 right-3 w-4 h-4 text-white/80 group-hover:text-white transition-colors duration-300 z-10"></i>
                </div>
              </div>
            </div>
          </div>

          {/* Right Column */}
          <div className="w-full lg:w-1/2 relative animate-slide-left delay-700">
            <img src="https://cdn.midjourney.com/1dd6f5e0-0973-4b64-a757-56af98dc2d42/0_0.png?w=800&q=80" alt="Hero Agent" className="w-full h-full min-h-[400px] lg:min-h-full object-cover" />
            
            {/* Gradient overlay */}
            <div className="absolute inset-0 bg-gradient-to-t from-black/30 via-transparent to-transparent"></div>

            {/* Overlay Badge */}
            <div className="absolute bottom-6 left-1/2 -translate-x-1/2 flex items-center gap-2 bg-white/90 backdrop-blur-sm text-xs font-medium px-4 py-2 rounded-lg shadow-lg border border-white/20 animate-fade-in delay-800 font-geist">
              <i data-lucide="brain" className="w-4 h-4 text-gray-900"></i>
              optimized for agents &amp; humans
            </div>

            {/* Status indicators */}
            <div className="absolute top-6 right-6 flex flex-col gap-2">
              <div className="flex items-center gap-2 bg-green-500/90 text-white text-xs px-3 py-1 rounded-full font-geist">
                <div className="w-2 h-2 bg-white rounded-full animate-pulse"></div>
                ACTIVE
              </div>
              <div className="flex items-center gap-2 bg-blue-500/90 text-white text-xs px-3 py-1 rounded-full font-geist">
                <i data-lucide="zap" className="w-3 h-3"></i>
                LEARNING
              </div>
            </div>
          </div>

        </div>

        {/* Mobile Menu Toggle */}
        <button className="md:hidden fixed top-4 right-4 z-50 p-2 bg-black text-white rounded-lg">
          <i data-lucide="menu" className="w-5 h-5"></i>
        </button>

        <script>
          {`lucide.createIcons();`}
        </script>

      </body>
    </html>
  );
}
