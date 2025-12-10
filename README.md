mkdir prueba

cd prueba

git clone https://web_del_proyecto.git .  
-> Te lo bajas en tu pc al directorio que acabas de crear y que estás dentro

mkdir "mi_nuevo_directorio_con_o_sin_contenido"  -> debe de estar dentro del directorio 
anterior para que el próximo comando no dé error

git add "mi_nuevo_directorio_con_o_sin_contenido"

git commit -m "Nuevo directorio"

git push origin
