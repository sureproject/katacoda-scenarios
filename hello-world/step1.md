## วิธีการติดตั้ง Minikube

สามารถติดตั้ง Minikube โดยดาวน์โหลดมาด้วยคำสั่งนี้

`curl -Lo minikube https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64`{{execute}}

ตั้งค่าให้ minikube สามารถทำงานได้ ด้วยคำสั่ง

`chmod +x minikube`{{execute}}

จากนั้นทำการเพิ่ม Minikube ไปที่ /usr/local/bin เพื่อจะทำการเรียกใช้ได้ง่าย

`sudo cp minikube /usr/local/bin && rm minikube`{{execute}}
