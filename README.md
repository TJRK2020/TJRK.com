function showSizeGuide() {
    document.getElementById('size-guide').classList.remove('hidden');
}

function hideSizeGuide() {
    document.getElementById('size-guide').classList.add('hidden');
}

document.getElementById('payment-form').addEventListener('submit', function(event) {
    event.preventDefault();
    alert('Payment processing... (this is a demo)');
});
