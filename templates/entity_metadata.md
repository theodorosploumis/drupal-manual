# Entity Metadata Tables

## Node type

| Entity Type | Machine name | Description | Fields | Form Mode screenshot | View Mode screenshot | Actions | Options |
| ----------- | ------------ | ----------- | ------ | -------------------- | -------------------- | ------- | ------- |
| Node: Page  | page | A static content... | [title](#fields-title), [body](#fields-body) | (IMAGE) | (IMAGE) | [Add New](#actions-add-new), Delete, Edit, Replicate | [Published](#options-published), Author |


## Node type Actions

| Entity Type | Action | Description | URL | Frontend button | Backend button |
| ----------- | ------ | ----------- | --- | --------------- | -------------- |
| Node: Page   | Add New | Adds a new Node of type Page | /node/add/page | (IMAGE) | (IMAGE) |


## Node type Options

| Option | Description | Type | Form Mode screenshot |
| ------ | ----------- | ---- | -------------------- |
| Published | Enables/Disables the public access to a node | checkbox | (IMAGE) |


---

## Fields

| Field name | Machine name | Description | Type | Form Mode screenshot | View Mode screenshot | Cardinality | Required |
| ---------- | ------------ | ----------- | ---- | -------------------- | -------------------- | ----------- | -------- |
| title  | label | Node title | textfield | (IMAGE) | (IMAGE) | 1 | Yes |
