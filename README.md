You said:
/home/sakthees-monk/Downloads/android-studio-2025.1.1.13-linux.tar.gz unzip usr/local giveterminal prompt and install
ChatGPT said:
To install Android Studio from the .tar.gz file you downloaded (android-studio-2025.1.1.13-linux.tar.gz) to /usr/local, follow these terminal commands:

✅ Step-by-step Terminal Commands
# 1. Go to your Downloads folder
cd ~/Downloads

# 2. Extract the tar.gz file to /usr/local (requires sudo)
sudo tar -xzvf android-studio-2025.1.1.13-linux.tar.gz -C /usr/local/

# 3. Go to the Android Studio bin directory
cd /usr/local/android-studio/bin

# 4. Run the Android Studio setup
./studio.sh

💡 Optional: Add to PATH permanently
To make it easier to launch Android Studio from the terminal using just studio.sh, you can add it to your PATH:
echo 'export PATH=$PATH:/usr/local/android-studio/bin' >> ~/.bashrc
source ~/.bashrc
If you're using zsh instead of bash, replace ~/.bashrc with ~/.zshrc.
sakthees-monk@saktheesmonk-desktop:/usr/local/android-studio/bin$ ./studio.sh
