Following command in Ghost core has been used to generate these files using [depcruise](https://github.com/sverweij/dependency-cruiser):
```
for svc in ghost/core/core/server/services/*; 
    do npx depcruise ghost --include-only "^ghost" --exclude "^(ghost/core/core/built|ghost/admin|test|ghost/core/core/server/data/migrations|ghost/core/test|ghost/core/core/server/web|ghost/core/core/server/api)" --focus "$svc" --output-type dot | dot -T svg > "{$PATH_TO_THIS_FOLDER}/$(basename $svc)-dependency-graph.svg"; 
done;
```
