## kubectl

    curl -Lo bin/kubectl https://storage.googleapis.com/kubernetes-release/release/$(curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt)/bin/linux/amd64/kubectl

## helm

    curl -Lo /tmp/helm-linux-amd64.tar.gz https://get.helm.sh/helm-v3.6.0-linux-amd64.tar.gz
    mkdir -p /tmp/helm-linux-amd64
    tar -xf /tmp/helm-linux-amd64.tar.gz -C /tmp/helm-linux-amd64
    cp /tmp/helm-linux-amd64/linux-amd64/helm bin/helm

## kubectx & kubens

    curl -Lo bin/kubectx https://raw.githubusercontent.com/ahmetb/kubectx/master/kubectx
    curl -Lo bin/kubens https://raw.githubusercontent.com/ahmetb/kubectx/master/kubens

## aws-iam-authenticator

    curl -Lo bin/aws-iam-authenticator https://amazon-eks.s3.us-west-2.amazonaws.com/1.19.6/2021-01-05/bin/linux/amd64/aws-iam-authenticator

## stern

    curl -Lo bin/stern https://github.com/wercker/stern/releases/download/1.11.0/stern_linux_amd64

## miniqube

    curl -Lo bin/minikube https://github.com/kubernetes/minikube/releases/download/v1.20.0/minikube-linux-amd64

## short

    curl -Lo bin/short https://github.com/koki/short/releases/download/0.5.1/short_linux_amd64

## Finally

    chmod +x bin/*

## (Optional) Install

    sudo install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl
