# MyHomeEnergyPlanner
My Home Energy Planner - Open Source home energy assessment software based on emoncms framework + openbem

    cd /var/www/emoncms/Modules
    git clone -b module https://github.com/emoncms/MyHomeEnergyPlanner.git assessment
    
    
    sudo ln -s /var/www/mhep/Modules/assessment/library/. /var/lib/mhep/master
    sudo chown -R www-data:www-data /var/lib/mhep/master
    sudo chown -R www-data:www-data /var/lib/mhep/master/.
