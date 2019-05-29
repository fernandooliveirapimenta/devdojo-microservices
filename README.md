# 1- instalar docker, com stack

# 2- mysql
      entrar na raiz do projeto pai
      subir: docker-compose -f course/stack.yml up -d
      parar: docker-compose -f course/stack.yml down
      
# 3- subir projetos
        primeiro: discovery
        segungo: gateway
        terceiro: auth
        ultimo: course
