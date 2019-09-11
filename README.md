# atlas1.1-restapi
atlas1.1-restapi


##### 1. create type1 & type2

```bash
curl -i -X POST -H 'Content-Type: application/json' -H 'Accept: application/json' -u admin:BadPass#1 'http://ec2-54-219-163-89.us-west-1.compute.amazonaws.com:21000/api/atlas/v2/types/typedefs' -d @type1.json

curl -i -X POST -H 'Content-Type: application/json' -H 'Accept: application/json' -u admin:BadPass#1 'http://ec2-54-219-163-89.us-west-1.compute.amazonaws.com:21000/api/atlas/v2/types/typedefs' -d @type2.json

```

##### 2. create entity1 & entity2

```bash
curl -i -X POST -H 'Content-Type: application/json' -H 'Accept: application/json' -u admin:BadPass#1 'http://ec2-54-219-163-89.us-west-1.compute.amazonaws.com:21000/api/atlas/v2/entity' -d @entity1.json

curl -i -X POST -H 'Content-Type: application/json' -H 'Accept: application/json' -u admin:BadPass#1 'http://ec2-54-219-163-89.us-west-1.compute.amazonaws.com:21000/api/atlas/v2/entity' -d @entity2.json

```

##### 3. create relationship type

```bash
curl -i -X POST -H 'Content-Type: application/json' -H 'Accept: application/json' -u admin:BadPass#1 'http://ec2-54-219-163-89.us-west-1.compute.amazonaws.com:21000/api/atlas/v2/types/typedefs' -d @relationship-type.json

```

##### 4. create relationship entiy

```bash
curl -i -X POST -H 'Content-Type: application/json' -H 'Accept: application/json' -u admin:BadPass#1 'http://ec2-54-219-163-89.us-west-1.compute.amazonaws.com:21000/api/atlas/v2/relationship' -d @relationship12.json

```

##### 1. create process type and process entity

```bash
curl -i -X POST -H 'Content-Type: application/json' -H 'Accept: application/json' -u admin:BadPass#1 'http://ec2-54-219-163-89.us-west-1.compute.amazonaws.com:21000/api/atlas/v2/types/typedefs' -d @type-process.json


curl -i -X POST -H 'Content-Type: application/json' -H 'Accept: application/json' -u admin:BadPass#1 'http://ec2-54-219-163-89.us-west-1.compute.amazonaws.com:21000/api/atlas/v2/entity' -d @entityProcess.json

```






afdf5e1e-0105-462e-ada4-58f0229733b8

8a33ba96-e69f-44d7-b567-6b3df4daa2d8





curl -i -X GET -H 'Content-Type: application/json' -H 'Accept: application/json' -u admin:BadPass#1 'http://ec2-54-219-163-89.us-west-1.compute.amazonaws.com:21000/api/atlas/v2/entity/guid/cbbaa344-637c-49c7-b254-b1683e01888f'





