## Cycle de vie

Pour les cas plus avancés :
* ngAfterContentInit : appelée lors que tous les bindings ont été vérifiés pour la première fois
* ngAfterContentChecked  : appelée lors que tous les bindings ont été vérifiés même s'ils n'ont pas changé
* ngAfterViewInit : appélée lorsque que tous les bindings des directives enfants ont été vérifiés pour la première fois
* ngAfterViewChecked : appélée lorsque que tous les bindings des directives enfants ont été vérifiés même s'ils n'ont pas changé
* ngDoCheck : appelée à chaque cycle de détection

