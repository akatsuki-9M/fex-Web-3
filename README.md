# fex-Web-3
A Universal copy app of NeteaseMusic

How to start (如何开始)
clone project to local

git clone https://github.com/boyan01/flutter-netease-music.git 
install Flutter

require latest flutter stable channel.
build & run

flutter run --profile
Development (开发)
generate l10n
flutter pub global activate intl_utils
flutter pub global run intl_utils:generate
Linux requirement.
debian:

sudo apt install libavcodec-dev libavformat-dev libavdevice-dev
sudo apt-get install libsdl2-dev
Dependency backend
Toast and InApp notification： overlay_support
music player(mobile): flutter-music-player
music player(desktop): lychee_player
netease api service: NeteaseCloudMusicApi
Desktop Preview
light	dark
playlist	playlist
playing	playing
Mobile Dark Mode Preview
main_playlist	playlist detail	add to playlist	artist_detail
album detail	playing cover	playing lyric	search
leaderboard	setting	search result	每日推荐
daily			
