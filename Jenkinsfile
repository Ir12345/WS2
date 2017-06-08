node {
git "https://github.com/Ir12345/WS2.git"
def mvnHome = tool "Maven"
stage (Build & Deploy) {sh "'${mvnHome}/bin/mvn' clean package tomcat7:" + stage}
}
