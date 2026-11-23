// 설치 가능한 홈 화면 앱을 위한 최소 서비스 워커입니다. 화면은 항상 인터넷으로 불러오고, 따로 저장하지 않습니다.
self.addEventListener('install', function () { self.skipWaiting(); });
self.addEventListener('activate', function (e) { e.waitUntil(self.clients.claim()); });
self.addEventListener('fetch', function () {});
