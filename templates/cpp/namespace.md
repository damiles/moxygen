# {{kind}} `{{name}}` {{anchor refid}}

{{briefdescription}}

## Summary

 Classes                        | Descriptions                                
--------------------------------|---------------------------------------------
{{#each filtered.compounds}}{{proto}}    | {{briefdescription}}
{{/each}}


 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
{{#each filtered.members}}{{cell proto}} | {{cell briefdescription}}
{{/each}}

## Members

{{#each filtered.members}}
### {{name}}
#### {{title proto}} {{anchor refid}}

{{briefdescription}}

{{detaileddescription}}

{{/each}}
