* wget -q -O - https://pkg.jenkins.io/debian/jenkins.io.key | sudo apt-key add -
* sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
* sudo apt update
* sudo apt install jenkins
* sudo systemctl start jenkins
* sudo systemctl enable jenkins
* sudo systemctl status jenkins

配置文件

* `/etc/default/jenkins`