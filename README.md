git clone https://github.com/psmk/psmk.git
cd psmk  # Masuk ke folder yang telah di-clone

echo '<iframe src="https://script.google.com/macros/s/AKfycbxCRpSjtGaNzsXd6v0e_YQTjcqGwUCCpe2-XCPsZiv3sbmozFy7qjYAE2C_9bjei688CA/exec" width="100%" height="500px"></iframe>' > psmk.html

git add psmk.html
git commit -m "Add psmk page"
git push origin main
