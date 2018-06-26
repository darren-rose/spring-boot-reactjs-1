cd src/main
npx create-react-app js
cd js
ln -s ./build ../resources/static
./gradlew jsInstall
./gradlew jsBuild
