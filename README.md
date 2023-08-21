<!DOCTYPE html>
<html>
<head>
    <title>Repositório de Estudo Kubernetes</title>
</head>
<body>
    <h1>Repositório de Estudo Kubernetes</h1>
    
    <h2>Configuração Inicial</h2>
    <p>Para começar a estudar Kubernetes, siga as instruções abaixo:</p>
    
    <h3>Passo 1: Baixe e Instale o Kind</h3>
    <p>Kind (Kubernetes in Docker) é uma ótima ferramenta para criar clusters Kubernetes locais para fins de desenvolvimento e estudo.</p>
    <p>Visite a página oficial do Kind: <a href="https://kind.sigs.k8s.io/">https://kind.sigs.k8s.io/</a></p>
    <p>Siga as instruções de instalação fornecidas na documentação para o seu sistema operacional.</p>
    
    <h3>Passo 2: Inicialize um Cluster Kubernetes</h3>
    <p>Após a instalação do Kind, você pode criar um cluster Kubernetes local com o seguinte comando:</p>
    
    <code>
        kind create cluster --name meu-cluster
    </code>
    
    <h3>Passo 3: Verifique o Cluster</h3>
    <p>Confirme se o cluster foi criado com sucesso executando o seguinte comando:</p>
    
    <code>
        kubectl cluster-info --context kind-meu-cluster
    </code>
    
    <h3>Passo 4: Comece a Explorar Kubernetes</h3>
    <p>Agora você está pronto para começar a explorar e estudar Kubernetes em seu cluster local. Consulte a documentação oficial do Kubernetes para aprender mais: <a href="https://kubernetes.io/docs/home/">https://kubernetes.io/docs/home/</a></p>
    
    <p>Divirta-se estudando Kubernetes!</p>

    <p>Comando usado para aplicar o deployment do projeto em questão:</p>
    
    <code>
        kubectl apply -f k8s/deployment.yaml
    </code>

    <p>Comando usado para aplicar o replicaset do projeto em questão:</p>
    
    <code>
        kubectl apply -f k8s/replicaset.yaml
    </code>

    <p>Comando usado para aplicar o pod do projeto em questão:</p>
    
    <code>
        kubectl apply -f k8s/pod.yaml
    </code>

    <b>No doc k8s.odt há alguns comando que possam ajudar !</b>
</body>
</html>
