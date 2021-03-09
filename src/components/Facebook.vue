<template>
    <div class="bg-gray-100">
        <header class="fixed w-full z-50">
            <nav class="flex justify-between items-center bg-white shadow-md">
                <div class="flex items-center px-4 py-2">
                    <svg class="text-white" viewBox="0 0 36 36" fill="url(#jsc_s_2)" height="40" width="40"><defs><linearGradient x1="50%" x2="50%" y1="97.0782153%" y2="0%" id="jsc_s_2"><stop offset="0%" stop-color="#0062E0"></stop><stop offset="100%" stop-color="#19AFFF"></stop></linearGradient></defs><path d="M15 35.8C6.5 34.3 0 26.9 0 18 0 8.1 8.1 0 18 0s18 8.1 18 18c0 8.9-6.5 16.3-15 17.8l-1-.8h-4l-1 .8z"></path><path class="p361ku9c" d="M25 23l.8-5H21v-3.5c0-1.4.5-2.5 2.7-2.5H26V7.4c-1.3-.2-2.7-.4-4-.4-4.1 0-7 2.5-7 7v4h-4.5v5H15v12.7c1 .2 2 .3 3 .3s2-.1 3-.3V23h4z"></path></svg>
                    <input type="text" class="ml-2 py-2 px-4 bg-gray-100 rounded-full text-gray-600 focus:outline-none w-60" placeholder="Search on Facebook">
                </div>
                <div class="flex flex-grow justify-around mx-2">
                    <a href="#" class="border-b-2 border-blue-500 pb-3 pt-3 mt-1 px-10">
                        <svg class="fill-current text-blue-500 w-6 h-6" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path d="M8 20H3V10H0L10 0l10 10h-3v10h-5v-6H8v6z"/></svg>
                    </a>
                    <a href="#" class="pt-3 px-10 hover:bg-gray-100 rounded-lg my-1 relative">
                        <svg class="fill-current text-gray-500 w-6 h-6" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path d="M2.93 17.07A10 10 0 1 1 17.07 2.93 10 10 0 0 1 2.93 17.07zm12.73-1.41A8 8 0 1 0 4.34 4.34a8 8 0 0 0 11.32 11.32zM7 6l8 4-8 4V6z"/></svg>
                        <span class="bg-red-500 absolute rounded-full text-white px-1 text-sm top-0 right-6">9+</span>
                    </a>
                    <a href="#" class="pt-3 px-10 hover:bg-gray-100 rounded-lg my-1">
                        <svg class="fill-current text-gray-500 w-6 h-6" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path d="M18 9.87V20H2V9.87a4.25 4.25 0 0 0 3-.38V14h10V9.5a4.26 4.26 0 0 0 3 .37zM3 0h4l-.67 6.03A3.43 3.43 0 0 1 3 9C1.34 9 .42 7.73.95 6.15L3 0zm5 0h4l.7 6.3c.17 1.5-.91 2.7-2.42 2.7h-.56A2.38 2.38 0 0 1 7.3 6.3L8 0zm5 0h4l2.05 6.15C19.58 7.73 18.65 9 17 9a3.42 3.42 0 0 1-3.33-2.97L13 0z"/></svg>                        
                    </a>
                    <a href="#" class="pt-3 px-10 hover:bg-gray-100 rounded-lg my-1">
                        <div class="rounded-full border-2 border-gray-500 p-1/2">
                            <svg class="w-5 h-5 text-gray-500 fill-current" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"></path></svg>
                        </div>
                    </a>
                    <a href="#" class="pt-3 px-10 hover:bg-gray-100 rounded-lg my-1 relative">
                        <svg class="fill-current text-gray-500 w-6 h-6" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path d="M0 0h9v9H0V0zm2 2v5h5V2H2zm-2 9h9v9H0v-9zm2 2v5h5v-5H2zm9-13h9v9h-9V0zm2 2v5h5V2h-5zm-2 9h9v9h-9v-9zm2 2v5h5v-5h-5z"/></svg>
                        <span class="bg-red-500 absolute rounded-full text-white px-1 text-sm top-0 right-6">9+</span>

                    </a>
                </div>
                <div>
                    <a href="#" class="flex items-center">
                        <img class="rounded-full w-7 h-7" src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t1.0-1/cp0/p80x80/82315401_10221385039072638_1539097244144238592_n.jpg?_nc_cat=103&ccb=2&_nc_sid=7206a8&_nc_ohc=sLOxxSDoIZEAX8oT8JD&_nc_ht=scontent.fcnx2-1.fna&tp=27&oh=d09b4b2a7a2d72683136da4f610f0767&oe=603D02F2" alt="">
                        <span class="ml-2 text-gray-900 font-semibold text-sm">Eakkawat</span>
                    </a>
                </div>
                <div class="flex mx-4">
                    <a href="#" >
                        <svg class="fill-current text-gray-900 rounded-full bg-gray-200 w-10 h-10 p-2" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6v6m0 0v6m0-6h6m-6 0H6" />
                        </svg>
                    </a>
                    <a href="#">
                        <svg class="ml-2 fill-current text-gray-900 rounded-full bg-gray-200 w-10 h-10 p-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                            <path fill-rule="evenodd" d="M18 5v8a2 2 0 01-2 2h-5l-5 4v-4H4a2 2 0 01-2-2V5a2 2 0 012-2h12a2 2 0 012 2zM7 8H5v2h2V8zm2 0h2v2H9V8zm6 0h-2v2h2V8z" clip-rule="evenodd" />
                        </svg>
                    </a>
                    <a href="#">
                        <svg class="ml-2 fill-current text-gray-900 rounded-full bg-gray-200 w-10 h-10 p-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                            <path d="M10 2a6 6 0 00-6 6v3.586l-.707.707A1 1 0 004 14h12a1 1 0 00.707-1.707L16 11.586V8a6 6 0 00-6-6zM10 18a3 3 0 01-3-3h6a3 3 0 01-3 3z" />
                        </svg>
                    </a>
                    <a href="#">
                        <svg class="ml-2 fill-current text-gray-900 rounded-full bg-gray-200 w-10 h-10 p-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                            <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
                        </svg>
                    </a>
                </div>
            </nav>
        </header>
        <main class="pt-14 flex justify-center min-h-screen">
            <aside class="m-4 fixed left-0">
                <ul>
                    <li class="py-3 pr-14 px-4 rounded-lg hover:bg-gray-200"><a class="font-semibold" href="#">Eakkawat Prommana</a></li>
                    <li class="py-3 pr-14 px-4 rounded-lg hover:bg-gray-200"><a class="font-semibold" href="#">Covid-19: info</a></li>
                    <li class="py-3 pr-14 px-4 rounded-lg hover:bg-gray-200"><a class="font-semibold" href="#">Pages</a></li>
                    <li class="py-3 pr-14 px-4 rounded-lg hover:bg-gray-200"><a class="font-semibold" href="#">Friends </a></li>
                    <li class="py-3 pr-14 px-4 rounded-lg hover:bg-gray-200"><a class="font-semibold" href="#">Marketplace</a></li>
                </ul>
            </aside>
            <section class="my-6">
                <div class="flex justify-around">
                    <a href="#" class="ml-2 relative w-28 h-42">
                        <div class="absolute rounded-lg bg-black opacity-0 hover:opacity-20 w-full h-full "></div>
                        <img class="rounded-lg w-full h-full" src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t15.5256-10/p235x165/131047783_3962304360466887_5721464940042291449_n.jpg?_nc_cat=108&ccb=2&_nc_sid=1055be&_nc_ohc=wESjQSXi0PgAX_dLYsU&_nc_ht=scontent.fcnx2-1.fna&oh=2802a2f8985ed7acb108ef8049695e39&oe=603C1029" alt="">
                    </a>
                    <a href="#" class="ml-2 relative w-28 h-42">
                        <div class="absolute rounded-lg w-full h-full" style="background-color: rgba(0, 0, 0, 0.5);">
                            <p class="absolute text-white bottom-3 w-full font-semibold text-left px-3 leading-5">THE STANDARD</p>
                        </div>
                        <img class="rounded-lg w-full h-full" src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t15.5256-10/p235x165/131047783_3962304360466887_5721464940042291449_n.jpg?_nc_cat=108&ccb=2&_nc_sid=1055be&_nc_ohc=wESjQSXi0PgAX_dLYsU&_nc_ht=scontent.fcnx2-1.fna&oh=2802a2f8985ed7acb108ef8049695e39&oe=603C1029" alt="">
                    </a>
                    <a href="#" class="ml-2 relative w-28 h-42">
                        <div class="absolute rounded-lg bg-black opacity-0 hover:opacity-20 w-full h-full"></div>
                        <img class="rounded-lg w-full h-full" src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t15.5256-10/p235x165/131047783_3962304360466887_5721464940042291449_n.jpg?_nc_cat=108&ccb=2&_nc_sid=1055be&_nc_ohc=wESjQSXi0PgAX_dLYsU&_nc_ht=scontent.fcnx2-1.fna&oh=2802a2f8985ed7acb108ef8049695e39&oe=603C1029" alt="">
                    </a>
                    <a href="#" class="ml-2 relative w-28 h-42">
                        <div class="absolute rounded-lg bg-black opacity-0 hover:opacity-20 w-full h-full"></div>
                        <img class="rounded-lg w-full h-full" src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t15.5256-10/p235x165/131047783_3962304360466887_5721464940042291449_n.jpg?_nc_cat=108&ccb=2&_nc_sid=1055be&_nc_ohc=wESjQSXi0PgAX_dLYsU&_nc_ht=scontent.fcnx2-1.fna&oh=2802a2f8985ed7acb108ef8049695e39&oe=603C1029" alt="">
                    </a>
                    <a href="#" class="ml-2 relative w-28 h-42">
                        <div class="absolute rounded-lg bg-black opacity-0 hover:opacity-20 w-full h-full"></div>
                        <img class="rounded-lg w-full h-full" src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t15.5256-10/p235x165/131047783_3962304360466887_5721464940042291449_n.jpg?_nc_cat=108&ccb=2&_nc_sid=1055be&_nc_ohc=wESjQSXi0PgAX_dLYsU&_nc_ht=scontent.fcnx2-1.fna&oh=2802a2f8985ed7acb108ef8049695e39&oe=603C1029" alt="">
                        <button class="absolute rounded-full bg-white hover:bg-gray-200 w-12 h-12 top-16 -right-6 shadow-lg">
                            <svg class="w-4 h-4 m-auto fill-current" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
                        </button>
                       
                    </a>
                </div>
                <div style="max-width: 40rem;">
                    <div class="bg-white rounded-lg px-4 py-4 mt-6 mx-12 shadow-md">
                        <div class="border-b border-gray-200 flex pb-3">
                            <img class="rounded-full w-10 h-10" src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t1.0-1/cp0/p60x60/82315401_10221385039072638_1539097244144238592_n.jpg?_nc_cat=103&ccb=2&_nc_sid=7206a8&_nc_ohc=sLOxxSDoIZEAX-8Fa4f&_nc_ht=scontent.fcnx2-1.fna&tp=27&oh=635c784264d0236a5c6ff5546cdaa0fb&oe=603D03A1" alt="user picture">
                            <button type="button" class="bg-gray-100 text-lg rounded-3xl flex-grow ml-2 focus:outline-none text-left px-4 py-1 text-gray-700">What's on your mind ?</button>
                        </div>
                        <div class="flex mt-2 text-gray-500 font-semibold">
                            <div class="flex justify-center items-center cursor-pointer w-1/2 rounded-lg hover:bg-gray-100 py-2 ">
                                <svg class="w-8 h-8 text-red-500" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 10l4.553-2.276A1 1 0 0121 8.618v6.764a1 1 0 01-1.447.894L15 14M5 18h8a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v8a2 2 0 002 2z"></path></svg>
                                <span class="ml-2">Live video</span>
                            </div>
                            <div class="flex justify-center items-center cursor-pointer w-1/2 rounded-lg hover:bg-gray-100 py-2">
                                <svg class="w-8 h-8 text-green-400" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16l4.586-4.586a2 2 0 012.828 0L16 16m-2-2l1.586-1.586a2 2 0 012.828 0L20 14m-6-6h.01M6 20h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z"></path></svg>
                                <span class="ml-2">Photo/Video</span>
                            </div>
                            <div class="flex justify-center items-center cursor-pointer w-1/2 rounded-lg hover:bg-gray-100 py-2">
                                <svg class="w-8 h-8 text-yellow-400" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14.828 14.828a4 4 0 01-5.656 0M9 10h.01M15 10h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>                            
                                <span class="ml-2">Feeling/Activity</span>
                            </div>
                        </div>
                    </div>
                    <div class="flex items-center bg-white rounded-lg px-4 py-4 mt-4 mx-12 shadow-md pr-0">
                        <button class="text-blue-500 py-2 px-4 rounded-3xl border-2 border-blue-100 font-semibold">Create Room</button>
                        <div class="flex items-center ml-2 overflow-hidden" style="max-width: 22rem;">
                            <img class="rounded-full mx-2 w-10 h-10" src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t1.0-1/cp0/p60x60/82315401_10221385039072638_1539097244144238592_n.jpg?_nc_cat=103&ccb=2&_nc_sid=7206a8&_nc_ohc=sLOxxSDoIZEAX-8Fa4f&_nc_ht=scontent.fcnx2-1.fna&tp=27&oh=635c784264d0236a5c6ff5546cdaa0fb&oe=603D03A1" alt="user picture">
                            <img class="rounded-full mx-2 w-10 h-10" src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t1.0-1/cp0/p60x60/82315401_10221385039072638_1539097244144238592_n.jpg?_nc_cat=103&ccb=2&_nc_sid=7206a8&_nc_ohc=sLOxxSDoIZEAX-8Fa4f&_nc_ht=scontent.fcnx2-1.fna&tp=27&oh=635c784264d0236a5c6ff5546cdaa0fb&oe=603D03A1" alt="user picture">
                            <img class="rounded-full mx-2 w-10 h-10" src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t1.0-1/cp0/p60x60/82315401_10221385039072638_1539097244144238592_n.jpg?_nc_cat=103&ccb=2&_nc_sid=7206a8&_nc_ohc=sLOxxSDoIZEAX-8Fa4f&_nc_ht=scontent.fcnx2-1.fna&tp=27&oh=635c784264d0236a5c6ff5546cdaa0fb&oe=603D03A1" alt="user picture">
                            <img class="rounded-full mx-2 w-10 h-10" src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t1.0-1/cp0/p60x60/82315401_10221385039072638_1539097244144238592_n.jpg?_nc_cat=103&ccb=2&_nc_sid=7206a8&_nc_ohc=sLOxxSDoIZEAX-8Fa4f&_nc_ht=scontent.fcnx2-1.fna&tp=27&oh=635c784264d0236a5c6ff5546cdaa0fb&oe=603D03A1" alt="user picture">
                            <img class="rounded-full mx-2 w-10 h-10" src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t1.0-1/cp0/p60x60/82315401_10221385039072638_1539097244144238592_n.jpg?_nc_cat=103&ccb=2&_nc_sid=7206a8&_nc_ohc=sLOxxSDoIZEAX-8Fa4f&_nc_ht=scontent.fcnx2-1.fna&tp=27&oh=635c784264d0236a5c6ff5546cdaa0fb&oe=603D03A1" alt="user picture">
                            <img class="rounded-full mx-2 w-10 h-10" src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t1.0-1/cp0/p60x60/82315401_10221385039072638_1539097244144238592_n.jpg?_nc_cat=103&ccb=2&_nc_sid=7206a8&_nc_ohc=sLOxxSDoIZEAX-8Fa4f&_nc_ht=scontent.fcnx2-1.fna&tp=27&oh=635c784264d0236a5c6ff5546cdaa0fb&oe=603D03A1" alt="user picture">
                            <img class="rounded-full mx-2 w-10 h-10" src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t1.0-1/cp0/p60x60/82315401_10221385039072638_1539097244144238592_n.jpg?_nc_cat=103&ccb=2&_nc_sid=7206a8&_nc_ohc=sLOxxSDoIZEAX-8Fa4f&_nc_ht=scontent.fcnx2-1.fna&tp=27&oh=635c784264d0236a5c6ff5546cdaa0fb&oe=603D03A1" alt="user picture">
                        </div>
                    </div>
                    <div class="bg-white rounded-lg px-4 py-4 mt-4 mx-12 shadow-md">
                        <div class="flex items-center justify-between">
                            <div class="flex">
                                <img class="rounded-full w-10 h-10" src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t15.5256-10/p235x165/131047783_3962304360466887_5721464940042291449_n.jpg?_nc_cat=108&ccb=2&_nc_sid=1055be&_nc_ohc=wESjQSXi0PgAX_dLYsU&_nc_ht=scontent.fcnx2-1.fna&oh=2802a2f8985ed7acb108ef8049695e39&oe=603C1029" alt="">
                                <div class="ml-2">
                                    <p class="text-gray-800 font-semibold">Tae'Fantasy TR</p>
                                    <p class="text-gray-500 text-sm flex items-center">
                                        <span>2 hrs</span>
                                        <span class="ml-1">&middot;</span>
                                        <svg class="ml-1 w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3.055 11H5a2 2 0 012 2v1a2 2 0 002 2 2 2 0 012 2v2.945M8 3.935V5.5A2.5 2.5 0 0010.5 8h.5a2 2 0 012 2 2 2 0 104 0 2 2 0 012-2h1.064M15 20.488V18a2 2 0 012-2h3.064M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                                    </p>
                                </div>
                            </div>
                            <div>
                                <button class="hover:bg-gray-200 rounded-full w-10 h-10">
                                    <svg class="w-6 h-6 m-auto text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 12h.01M12 12h.01M19 12h.01M6 12a1 1 0 11-2 0 1 1 0 012 0zm7 0a1 1 0 11-2 0 1 1 0 012 0zm7 0a1 1 0 11-2 0 1 1 0 012 0z"></path></svg>
                                </button>
                            </div>
                        </div>
                        <div class="mt-2">
                            <p class="text-gray-800">ขอสอบถามหน่อยครับ ผมกำลังฝึกทำ CRUD แต่ติดปัญหาตรงนี้</p>
                        </div>
                        <div class="mt-2">
                            <img src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t1.0-9/p960x960/143860893_3706608166099162_9157739095794451337_o.jpg?_nc_cat=107&ccb=2&_nc_sid=825194&_nc_ohc=wLXI6iCi3hcAX9thdzV&_nc_ht=scontent.fcnx2-1.fna&tp=6&oh=00e14650f366e7439f0cbd400517418f&oe=603E6FC3" alt="">
                        </div>
                        <div class="flex items-center justify-between mt-2 px-2 text-gray-600">
                            <div class="flex items-center">
                                <button type="button" class="rounded-full bg-blue-500 w-5 h-5 p-1">
                                    <svg class="w-full h-full text-white m-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 10h4.764a2 2 0 011.789 2.894l-3.5 7A2 2 0 0115.263 21h-4.017c-.163 0-.326-.02-.485-.06L7 20m7-10V5a2 2 0 00-2-2h-.095c-.5 0-.905.405-.905.905 0 .714-.211 1.412-.608 2.006L7 11v9m7-10h-2M7 20H5a2 2 0 01-2-2v-6a2 2 0 012-2h2.5"></path></svg>
                                </button>
                                <a href="#" class="ml-2 hover:underline">3</a>
                            </div>
                            <div class="flex">
                                <a href="#" class="hover:underline">13 Comments</a>
                                <a href="#" class="ml-2 hover:underline">5 Shares</a>
                            </div>
                        </div>
                        <div class="flex justify-between mt-2 border-t border-b border-gray-300 py-1">
                            <button class="rounded-lg hover:bg-gray-200 flex-grow text-gray-700 font-semibold py-2">Like</button>
                            <button class="rounded-lg hover:bg-gray-200 flex-grow text-gray-700 font-semibold py-2">Comment</button>
                            <button class="rounded-lg hover:bg-gray-200 flex-grow text-gray-700 font-semibold py-2">Share</button>
                        </div>
                        <div class="mt-2 flex justify-end">
                            <a href="#" class="flex items-baseline font-semibold text-gray-700">
                                <span>Most relavant</span>
                                <svg class="w-3 h-3 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                            </a>
                        </div>
                        <div class="flex mt-2">
                            <img class="rounded-full w-8 h-8" src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t15.5256-10/p235x165/131047783_3962304360466887_5721464940042291449_n.jpg?_nc_cat=108&ccb=2&_nc_sid=1055be&_nc_ohc=wESjQSXi0PgAX_dLYsU&_nc_ht=scontent.fcnx2-1.fna&oh=2802a2f8985ed7acb108ef8049695e39&oe=603C1029" alt="">
                            <input type="text" class="ml-2 flex-grow bg-gray-100 rounded-3xl py-2 px-4 focus:outline-none" placeholder="Write a comment...">
                        </div>
                        <div class="mt-2">
                            <div class="mt-2">
                                <div class="flex items-start mt-1">
                                    <img class="rounded-full w-8 h-8" src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t15.5256-10/p235x165/131047783_3962304360466887_5721464940042291449_n.jpg?_nc_cat=108&ccb=2&_nc_sid=1055be&_nc_ohc=wESjQSXi0PgAX_dLYsU&_nc_ht=scontent.fcnx2-1.fna&oh=2802a2f8985ed7acb108ef8049695e39&oe=603C1029" alt="">
                                    <div class="flex items-center">
                                        <div class="ml-2">
                                            <div class="rounded-3xl bg-gray-100 p-3 max-w-sm">
                                                <p class="text-gray-900 text-sm font-semibold">อภิเดช ชารีงาม</p>
                                                <p class="text-gray-900 leading-5">ไป set default null ในฟิลด์นั้นที่อยุ่ใน table ครับ ไม่งั้นถ้าไม่มีค่าไปมันจะแจ้งแบบนี้แหละ</p>
                                            </div>
                                             <div class="flex items-center text-gray-500 font-semibold text-sm pl-3">
                                                <a href="#">Like</a>
                                                <span class="mx-1">&middot;</span>
                                                <a href="#">Reply</a>
                                                <span class="mx-1">&middot;</span>
                                                <span class="font-normal">3 hrs.</span>
                                            </div>
                                        </div>
                                        <button class="rounded-full hover:bg-gray-100 p-1 ml-1">
                                            <svg class="w-5 h-5 m-auto text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 12h.01M12 12h.01M19 12h.01M6 12a1 1 0 11-2 0 1 1 0 012 0zm7 0a1 1 0 11-2 0 1 1 0 012 0zm7 0a1 1 0 11-2 0 1 1 0 012 0z"></path></svg>
                                        </button>
                                    </div>
                                </div>
                                <div class="flex justify-between mt-2">
                                    <a class="text-gray-700 font-semibold" href="#">View more comments</a>
                                    <span>2 of 35</span>
                                </div>
                            </div>
                            <div></div>
                        </div>
                    </div>
                </div>
            </section>
            <aside class="m-4 fixed right-0">
                <div class="border-b border-gray-300 pb-2">
                    <h1 class="text-gray-500 font-bold pl-4">Birthday</h1>
                    <a href="#" class="font-semibold text-gray-900 block mt-2 py-2 px-4 rounded-lg hover:bg-gray-200">
                        <span class=" text-gray-600 font-normal">Today is birthday of</span>
                        Looked Looked
                    </a>
                </div>
                <div class="mt-4">
                    <h1 class="text-gray-500 font-bold pl-4">Contacts</h1>
                    <ul class="mt-2">
                        <li class="py-3 px-4 hover:bg-gray-200 rounded-lg flex">
                            <div class="relative">
                                <img class="rounded-full w-7 h-7" src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t1.0-1/cp0/s56x56/118011828_3508326532531341_2634792442163657353_n.jpg?_nc_cat=100&ccb=2&_nc_sid=7206a8&_nc_ohc=pgOBugCU28EAX94vjWA&_nc_ht=scontent.fcnx2-1.fna&tp=28&oh=b9aa442ea08008edc8cf9f94aac0c776&oe=603A4FC8" alt="">
                                <span class="w-2.5 h-2.5 rounded-full bg-green-400 absolute bottom-0 right-0 border-2"></span>
                            </div>
                            <a class="text-gray-900 font-semibold ml-2" href="#">Parichart Prommana</a>
                        </li>
                        <li class="py-3 px-4 hover:bg-gray-200 rounded-lg flex">
                            <div class="relative">
                                <img class="rounded-full w-7 h-7" src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t1.0-1/cp0/s56x56/118011828_3508326532531341_2634792442163657353_n.jpg?_nc_cat=100&ccb=2&_nc_sid=7206a8&_nc_ohc=pgOBugCU28EAX94vjWA&_nc_ht=scontent.fcnx2-1.fna&tp=28&oh=b9aa442ea08008edc8cf9f94aac0c776&oe=603A4FC8" alt="">
                                <span class="w-2.5 h-2.5 rounded-full bg-green-400 absolute bottom-0 right-0 border-2"></span>
                            </div>
                            <a class="text-gray-900 font-semibold ml-2" href="#">Parichart Prommana</a>
                        </li>
                        <li class="py-3 px-4 hover:bg-gray-200 rounded-lg flex">
                            <div class="relative">
                                <img class="rounded-full w-7 h-7" src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t1.0-1/cp0/s56x56/118011828_3508326532531341_2634792442163657353_n.jpg?_nc_cat=100&ccb=2&_nc_sid=7206a8&_nc_ohc=pgOBugCU28EAX94vjWA&_nc_ht=scontent.fcnx2-1.fna&tp=28&oh=b9aa442ea08008edc8cf9f94aac0c776&oe=603A4FC8" alt="">
                                <span class="w-2.5 h-2.5 rounded-full bg-green-400 absolute bottom-0 right-0 border-2"></span>
                            </div>
                            <a class="text-gray-900 font-semibold ml-2" href="#">Parichart Prommana</a>
                        </li>
                        <li class="py-3 px-4 hover:bg-gray-200 rounded-lg flex">
                            <div class="relative">
                                <img class="rounded-full w-7 h-7" src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t1.0-1/cp0/s56x56/118011828_3508326532531341_2634792442163657353_n.jpg?_nc_cat=100&ccb=2&_nc_sid=7206a8&_nc_ohc=pgOBugCU28EAX94vjWA&_nc_ht=scontent.fcnx2-1.fna&tp=28&oh=b9aa442ea08008edc8cf9f94aac0c776&oe=603A4FC8" alt="">
                                <span class="w-2.5 h-2.5 rounded-full bg-green-400 absolute bottom-0 right-0 border-2"></span>
                            </div>
                            <a class="text-gray-900 font-semibold ml-2" href="#">Parichart Prommana</a>
                        </li>
                        <li class="py-3 px-4 hover:bg-gray-200 rounded-lg flex">
                            <div class="relative">
                                <img class="rounded-full w-7 h-7" src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t1.0-1/cp0/s56x56/118011828_3508326532531341_2634792442163657353_n.jpg?_nc_cat=100&ccb=2&_nc_sid=7206a8&_nc_ohc=pgOBugCU28EAX94vjWA&_nc_ht=scontent.fcnx2-1.fna&tp=28&oh=b9aa442ea08008edc8cf9f94aac0c776&oe=603A4FC8" alt="">
                                <span class="w-2.5 h-2.5 rounded-full bg-green-400 absolute bottom-0 right-0 border-2"></span>
                            </div>
                            <a class="text-gray-900 font-semibold ml-2" href="#">Parichart Prommana</a>
                        </li>
                    </ul>
                </div>
            </aside>
        </main>
    </div>
</template>
<script>
export default {
    
}
</script>