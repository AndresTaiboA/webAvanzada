# webAvanzada
# 1. No se recomienda trabajar en el main directamente porque ahí se mantiene una versión estable del código.
# 2. No se inicializa un segundo repositorio al usar --skip-git
# 3. npm run build compila el codigo
# 4. Revisar git status sirve para verificar que se está en la rama correcta antes de realizar el push
# 5. Se activa cada vez que se hace un pull request
# 6. runs-on representa la versión estable en la que el código trabajará
# 7. Se ejecuta npm antes ya que se necesitan todas las dependencias antes de poder ejecutar el código
# 8. Falla la etapa de las pruebas, por lo que las siguientes no se ejecutan
# 9. No se debería integrar ya que interferiría con la versión estable
# 10. package.json: variable/configuracion
#     API_URL pública: variable/configuracion
#     AWS_REGION: variable/configuracion
#     DB_PASSWORD: secreto/no versionable
#     API_TOKEN: versionable
#     terraform.tfstate: versionable