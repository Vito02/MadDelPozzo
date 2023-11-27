<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AR QR Code App</title>
    <script src="https://cdn.jsdelivr.net/npm/ar.js@2.3.0"></script>
    <script src="https://cdn.jsdelivr.net/npm/jsqr@1.0.1"></script>
</head>
<body>
    <a-scene embedded arjs="sourceType: webcam; debugUIEnabled: false;">
        <a-marker preset="hiro" jsqr>
            <!-- Aggiungi qui gli elementi della tua scena AR -->
            <a-box position="0 0.5 0" material="color: red;"></a-box>
        </a-marker>
    </a-scene>

 <script>
    document.addEventListener('DOMContentLoaded', function () {
        const scene = document.querySelector('a-scene');
        const marker = document.querySelector('a-marker');

        // Funzione per gestire la scansione del QR code
        function handleQRCode(data) {
            console.log('QR Code scansionato:', data);
            // Aggiungi qui la logica per gestire i dati del QR code e attivare l'oggetto in AR
            // Ad esempio, puoi cambiare la posizione dell'oggetto o aggiungerne altri.
            marker.setAttribute('position', '0 1 0');
        }

        // Inizializza il lettore di QR code
        const qrWorker = new Worker('https://cdn.jsdelivr.net/npm/jsqr@1.0.1/jsQR.worker.min.js');

        // Funzione per leggere i dati del QR code dalla fotocamera
        function readQRCode() {
            const canvas = scene.renderer.domElement;
            const imageData = scene.renderer.context.getImageData(0, 0, canvas.width, canvas.height);
            const code = jsQR(imageData.data, imageData.width, imageData.height);

            if (code) {
                handleQRCode(code.data);
            }

            requestAnimationFrame(readQRCode);
        }

        // Avvia la lettura del QR code
        readQRCode();
    });
</script>
</body>
</html>
