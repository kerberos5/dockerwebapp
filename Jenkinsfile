node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'giuliadi78') {

        def customImage = docker.build("giuliadi78/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
