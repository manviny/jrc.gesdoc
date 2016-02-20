#FIELDS
```json
{
    "bucket": {
        "id": 177,
        "type": "FieldtypeText",
        "flags": 0,
        "name": "bucket",
        "label": "",
        "collapsed": 0,
        "size": 0,
        "maxlength": 2048,
        "textformatters": "",
        "showIf": "",
        "columnWidth": 100,
        "required": "",
        "requiredIf": "",
        "stripTags": "",
        "placeholder": "",
        "pattern": ""
    },
    "bucketpath": {
        "id": 176,
        "type": "FieldtypeText",
        "flags": 0,
        "name": "bucketpath",
        "label": "",
        "description": "ruta a S3:\nnombrebucket/ (raiz del bucket)\nnombrebucket/empresa1/  (empresa dentro del bucket)",
        "collapsed": 0,
        "size": 0,
        "maxlength": 2048,
        "textformatters": "",
        "showIf": "",
        "columnWidth": 100,
        "required": "",
        "requiredIf": "",
        "stripTags": "",
        "placeholder": "",
        "pattern": ""
    },
    "challenge": {
        "id": 181,
        "type": "FieldtypeText",
        "flags": 0,
        "name": "challenge",
        "label": "",
        "collapsed": 0,
        "size": 0,
        "maxlength": 2048,
        "textformatters": "",
        "showIf": "",
        "columnWidth": 100,
        "required": "",
        "requiredIf": "",
        "stripTags": "",
        "placeholder": "",
        "pattern": ""
    },
    "fingerprint": {
        "id": 182,
        "type": "FieldtypeText",
        "flags": 0,
        "name": "fingerprint",
        "label": "",
        "collapsed": 0,
        "size": 0,
        "maxlength": 2048,
        "textformatters": "",
        "showIf": "",
        "columnWidth": 100,
        "required": "",
        "requiredIf": "",
        "stripTags": "",
        "placeholder": "",
        "pattern": ""
    },
    "key": {
        "id": 184,
        "type": "FieldtypeText",
        "flags": 0,
        "name": "key",
        "label": "",
        "collapsed": 0,
        "size": 0,
        "maxlength": 2048,
        "textformatters": "",
        "showIf": "",
        "columnWidth": 100,
        "required": "",
        "requiredIf": "",
        "stripTags": "",
        "placeholder": "",
        "pattern": ""
    },
    "prefix": {
        "id": 178,
        "type": "FieldtypeText",
        "flags": 0,
        "name": "prefix",
        "label": "",
        "collapsed": 0,
        "size": 0,
        "maxlength": 2048,
        "textformatters": "",
        "showIf": "",
        "columnWidth": 100,
        "required": "",
        "requiredIf": "",
        "stripTags": "",
        "placeholder": "",
        "pattern": ""
    },
    "secret": {
        "id": 185,
        "type": "FieldtypeText",
        "flags": 0,
        "name": "secret",
        "label": "",
        "collapsed": 0,
        "size": 0,
        "maxlength": 2048,
        "textformatters": "",
        "showIf": "",
        "columnWidth": 100,
        "required": "",
        "requiredIf": "",
        "stripTags": "",
        "placeholder": "",
        "pattern": ""
    },
    "sesion_id": {
        "id": 179,
        "type": "FieldtypeText",
        "flags": 0,
        "name": "sesion_id",
        "label": "",
        "collapsed": 0,
        "size": 0,
        "maxlength": 2048,
        "textformatters": "",
        "showIf": "",
        "columnWidth": 100,
        "required": "",
        "requiredIf": "",
        "stripTags": "",
        "placeholder": "",
        "pattern": ""
    },
    "ts": {
        "id": 183,
        "type": "FieldtypeText",
        "flags": 0,
        "name": "ts",
        "label": "",
        "collapsed": 0,
        "size": 0,
        "maxlength": 2048,
        "textformatters": "",
        "showIf": "",
        "columnWidth": 100,
        "required": "",
        "requiredIf": "",
        "stripTags": "",
        "placeholder": "",
        "pattern": ""
    }
}
```
#TEMPLATES
```json

{
    "aws": {
        "id": 100,
        "name": "aws",
        "fieldgroups_id": "aws",
        "flags": 0,
        "cache_time": 0,
        "useRoles": 0,
        "noInherit": 0,
        "childrenTemplatesID": 0,
        "sortfield": "",
        "noChildren": "",
        "noParents": "",
        "childTemplates": [

        ],
        "parentTemplates": [

        ],
        "allowPageNum": 0,
        "allowChangeUser": 0,
        "redirectLogin": 0,
        "urlSegments": 1,
        "https": 0,
        "slashUrls": 1,
        "slashPageNum": 0,
        "slashUrlSegments": 0,
        "altFilename": "",
        "guestSearchable": 0,
        "pageClass": "",
        "childNameFormat": "",
        "pageLabelField": "",
        "noGlobal": 0,
        "noMove": 0,
        "noTrash": 0,
        "noSettings": 0,
        "noChangeTemplate": 0,
        "noShortcut": 0,
        "noUnpublish": 0,
        "nameContentTab": 0,
        "noCacheGetVars": "",
        "noCachePostVars": "",
        "useCacheForUsers": 0,
        "cacheExpire": 0,
        "cacheExpirePages": [

        ],
        "cacheExpireSelector": "",
        "label": "",
        "tags": "",
        "titleNames": 0,
        "noPrependTemplateFile": 1,
        "noAppendTemplateFile": 1,
        "prependFile": "",
        "appendFile": "",
        "tabContent": "",
        "tabChildren": "",
        "nameLabel": "",
        "contentType": "",
        "_exportMode": true,
        "fieldgroupFields": [
            "title",
            "key",
            "secret",
            "body"
        ],
        "fieldgroupContexts": {
            "title": [

            ],
            "key": [

            ],
            "secret": [

            ],
            "body": [

            ]
        }
    },
    "aws_sesion": {
        "id": 103,
        "name": "aws_sesion",
        "fieldgroups_id": "aws_sesion",
        "flags": 0,
        "cache_time": 0,
        "useRoles": 0,
        "noInherit": 0,
        "childrenTemplatesID": 0,
        "sortfield": "",
        "noChildren": "",
        "noParents": "",
        "childTemplates": [

        ],
        "parentTemplates": [

        ],
        "allowPageNum": 0,
        "allowChangeUser": 0,
        "redirectLogin": 0,
        "urlSegments": 0,
        "https": 0,
        "slashUrls": 1,
        "slashPageNum": 0,
        "slashUrlSegments": 0,
        "altFilename": "",
        "guestSearchable": 0,
        "pageClass": "",
        "childNameFormat": "",
        "pageLabelField": "",
        "noGlobal": 0,
        "noMove": 0,
        "noTrash": 0,
        "noSettings": 0,
        "noChangeTemplate": 0,
        "noShortcut": 0,
        "noUnpublish": 0,
        "nameContentTab": 0,
        "noCacheGetVars": "",
        "noCachePostVars": "",
        "useCacheForUsers": 0,
        "cacheExpire": 0,
        "cacheExpirePages": [

        ],
        "cacheExpireSelector": "",
        "label": "",
        "tags": "",
        "titleNames": 0,
        "noPrependTemplateFile": 0,
        "noAppendTemplateFile": 0,
        "prependFile": "",
        "appendFile": "",
        "tabContent": "",
        "tabChildren": "",
        "nameLabel": "",
        "contentType": "",
        "_exportMode": true,
        "fieldgroupFields": [
            "title",
            "bucket",
            "prefix",
            "sesion_id",
            "ts",
            "challenge",
            "fingerprint"
        ],
        "fieldgroupContexts": {
            "title": [

            ],
            "bucket": [

            ],
            "prefix": [

            ],
            "sesion_id": [

            ],
            "ts": [

            ],
            "challenge": [

            ],
            "fingerprint": [

            ]
        }
    },
    "aws_user": {
        "id": 102,
        "name": "aws_user",
        "fieldgroups_id": "aws_user",
        "flags": 0,
        "cache_time": 0,
        "useRoles": 0,
        "noInherit": 0,
        "childrenTemplatesID": 0,
        "sortfield": "-published",
        "noChildren": "",
        "noParents": "",
        "childTemplates": [

        ],
        "parentTemplates": [

        ],
        "allowPageNum": 0,
        "allowChangeUser": 0,
        "redirectLogin": 0,
        "urlSegments": 0,
        "https": 0,
        "slashUrls": 1,
        "slashPageNum": 0,
        "slashUrlSegments": 0,
        "altFilename": "",
        "guestSearchable": 0,
        "pageClass": "",
        "childNameFormat": "",
        "pageLabelField": "",
        "noGlobal": 0,
        "noMove": 0,
        "noTrash": 0,
        "noSettings": 0,
        "noChangeTemplate": 0,
        "noShortcut": 0,
        "noUnpublish": 0,
        "nameContentTab": 0,
        "noCacheGetVars": "",
        "noCachePostVars": "",
        "useCacheForUsers": 0,
        "cacheExpire": 0,
        "cacheExpirePages": [

        ],
        "cacheExpireSelector": "",
        "label": "",
        "tags": "",
        "titleNames": 0,
        "noPrependTemplateFile": 0,
        "noAppendTemplateFile": 0,
        "prependFile": "",
        "appendFile": "",
        "tabContent": "",
        "tabChildren": "",
        "nameLabel": "",
        "contentType": "",
        "_exportMode": true,
        "fieldgroupFields": [
            "title",
            "bucketpath"
        ],
        "fieldgroupContexts": {
            "title": [

            ],
            "bucketpath": [

            ]
        }
    }
}
```
