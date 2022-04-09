# Project Workflow

## Setting up VM Environment

Step 1 - Initializing a VM using a vagrant box name from vagrant cloud.

Step 2 - Opening the vagrantfile to edit and enable public IP address using vim editor.

Step 3 -  Bringing up the VM. 

![IMG_9548](https://user-images.githubusercontent.com/93732510/162269164-92d2de00-28bc-4e5f-906c-d0d18ac280f5.jpg)

Step 4 - The VM is logged into via ssh.

![IMG_9607](https://user-images.githubusercontent.com/93732510/162562970-fbca8ed3-5e0c-47ca-bbcf-dbb0d4a119e3.jpg)

## Installing node.js

Step 1 - apt package manager is updated and upgraded.

![IMG_9608](https://user-images.githubusercontent.com/93732510/162563239-98138e63-916a-47ce-b709-c9f700ba1d13.jpg)

Step 2 - Certificates are added.

![IMG_9609](https://user-images.githubusercontent.com/93732510/162563290-ee8049fb-cc5d-4f05-83a9-21137b807b16.jpg)

![IMG_9610](https://user-images.githubusercontent.com/93732510/162563304-4882665d-b22c-4cc8-97f4-a0fbdc4bbfe0.jpg)

Step 3 -  NodeJS is installed.

![IMG_9612](https://user-images.githubusercontent.com/93732510/162563381-745f3792-0fce-4723-991f-9f5e2533f2c7.jpg)

## MongoDB Installation

Step 1 - Installing Mongodb

![IMG_9613](https://user-images.githubusercontent.com/93732510/162563825-98b1617f-7576-46a5-9434-dbb5411fdffe.jpg)

![IMG_9614](https://user-images.githubusercontent.com/93732510/162563848-f3d8a7bc-d927-495f-90ae-4fcfd886831b.jpg)

![IMG_9614 2](https://user-images.githubusercontent.com/93732510/162563878-823a0029-e86f-45bd-b40d-ced194175107.jpg)

Step 2 - The mongodb service is started and checked for verification.

Step 3 - body-parser package is installed to help in processing JSON files passed in requests to the server.

![IMG_9617](https://user-images.githubusercontent.com/93732510/162564066-22bb7750-97f0-4be0-aca3-9a64c8029cf7.jpg)

Step 4 - A directory for the application is created and npm initialized in it.

![IMG_9618](https://user-images.githubusercontent.com/93732510/162564202-1457bdf5-8849-49d2-b069-e0ef0cf93454.jpg)

Step 5 - Server.js file is created and server code copied into it.

![IMG_9618](https://user-images.githubusercontent.com/93732510/162564284-27d755fb-c8ea-4e55-988b-725eddcffe5e.jpg)

## Express installtion and server routing

Step 1 - Installing express and mongoose.

![IMG_9621](https://user-images.githubusercontent.com/93732510/162564447-776452d4-459a-4209-9578-93c0e5a07cea.jpg)

Step 2 - Application directory is created, route.js file is created where the code is then copied into.

![IMG_9623](https://user-images.githubusercontent.com/93732510/162564551-6fd95d9c-1264-4952-a6e1-fe609c2882e2.jpg)

![IMG_9622](https://user-images.githubusercontent.com/93732510/162564564-cc9c00de-f3e1-4ff2-a076-1292be235a8b.jpg)

Step 3 - Models directory is created, books.js file is created where the code is then copied into.

![IMG_9625](https://user-images.githubusercontent.com/93732510/162564650-02a94041-9f2b-4079-acd8-cc1217720579.jpg)

![IMG_9624](https://user-images.githubusercontent.com/93732510/162564668-b5d6b50f-def1-44dd-a09c-cfe216bca35a.jpg)

Step 4 - Public directory is created, script.js file is created where the code is then copied into.

![IMG_9626](https://user-images.githubusercontent.com/93732510/162564761-0cd88239-c4fd-496e-90b3-504f92da736f.jpg)

![IMG_9627](https://user-images.githubusercontent.com/93732510/162564809-ee249efc-959c-4f26-8c8b-9698069d1fe9.jpg)

Step 5 - In the same public directory, index.html file is created where the code is then copied into.

![IMG_9629](https://user-images.githubusercontent.com/93732510/162564958-de31dbbf-f58e-435f-a150-87637cdb4585.jpg)

![IMG_9628](https://user-images.githubusercontent.com/93732510/162564978-47a270c8-523a-4c8e-944c-3362b3e0f0cd.jpg)

Step 6 - Now the server is then started.

![IMG_9636](https://user-images.githubusercontent.com/93732510/162565041-d8ec2e24-4d78-4787-a3c0-56d901e10f47.jpg)

Step 7 - The output is checked via browser using the public IP address and port number.

![IMG_9631](https://user-images.githubusercontent.com/93732510/162565119-08f2a464-a4b4-40e1-946d-334c5d56cb46.jpg)
