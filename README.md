# odoo-material_ARA
ekstrak zip nya 
penginstalan menggunakan docker-compose up -d melalui terminal
kemudian docker-compose restart
silahkan masuk localhost:8021
kemudian install material
lalu apabila melakukan unit-test dengan perintah docker-compose run unit-test odoo -u material -d test --test-enable --stop-after-init --log-level=test --test-tags=material.material_test_models --test-file=/mnt/extra-addons/test/material/tests/test_models.py

