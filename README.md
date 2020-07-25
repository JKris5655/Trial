const allUrls = [
    'https://www.google.com',
    'https://www.facebook.com',
    'https://www.cnn.com',
    'https://www.abc.com'
];

$w.onReady(function(){
    const randomIndex = Math.floor(Math.random() * (allUrls.length - 1));
    $w('#button1').link = allUrls[randomIndex];
});
