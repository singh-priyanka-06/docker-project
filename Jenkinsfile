node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'priyankas06') {

        def customImage = docker.build("priyankas06/dockerubuntu")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
