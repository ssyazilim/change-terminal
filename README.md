# change-terminal
[echo $SHELL] komutu ile hangi shelli kullandigina bakabilirsin. <br />
[sudo apt install zsh] komutu ile zsh shell yuklemesi yap [zsh --version] komutu ile yuklenip yuklenmedigini check et. <br />
[sudo apt install curl wget git vim mc htop neofetch] ile ilgili paketlerin yuklemesini tamamla. <br />
[sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"] komutu ile oh my zsh yuklemesini gerceklestir. <br />
[git clone --depth=1 https://github.com/romkatv/powerlevel10k.git "${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k"] Daha sonra powerlevel10k temasini yukle <br />
[vim ~/.zshrc] komutunu calistir ve ZSH_THEME="powerlevel10k/powerlevel10k" olarak guncelle <br />
[p10k configure] komutu ile shell ekranini degistirebilirsin genellikle hep ilk cikanlari sec digerleri bok gibi
