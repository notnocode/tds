# TDS | CLI

**under development 🏗️**

| Feautre       | Command           |
| ------------- | ----------------- |
| Add todo      | tds add todo_test |
| List Todos    | tds ls            |
| Search/Filter | future            |
| Archive       | future            |
| Edit          | future            |

## Adding

tds add "Add Priorities"
tds add \ "Add Mutli Todo Support" \ "hmm"
tds add -p1 "Add listing"
tds "Add listing P:1"

## Listing

tds li
tds list

## Priority System

High, Middle, Low
H=1, L=3, M/\_=2
Default is 2

## Filtering

- with tokens
  :tds list done

- with flahs

tds list -p1
tds list --due June
tds list --created 12/15
tds list --done -p1

## Searching

tds list "Add" "Pri"

## Completing

tds done 2

## Editing

tds edit 1 "Improve Listing"
tds edit 1 -p2
tds edit 2 --due 05/13/15
tds edit 3 --created 12/15

## Consistency

tds edit 1 -p2
tds list -p2
tds edit 3 --created 12/15
tds list --created 12/15

## Batch edit

tds edit 1 2 3 -p2
