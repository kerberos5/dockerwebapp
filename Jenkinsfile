node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerhub') {

        def customImage = docker.build("giuliadi78/docker-test")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
