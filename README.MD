
# Documentação simples API BetShield Provider

Uma breve descrição.

## Listagem de provedores

```javascript

(async()=>{
const res = await fetch("https://bsigaming.online/api/providers", {
  "headers": {
    "accept": "*/*",
    "accept-language": "pt-BR,pt;q=0.9,en-US;q=0.8,en;q=0.7,ar;q=0.6",
    "content-type": "application/x-www-form-urlencoded",
    "Api-Key":"{{token}}"
  },

  "referrerPolicy": "strict-origin-when-cross-origin",
  "method": "GET",
  "mode": "cors",
  "credentials": "omit"
});
   console.log(await res.json()); 
})();

```

## Listagem de jogos

```javascript

(async()=>{
const res = await fetch("https://bsigaming.online/api/games", {
  "headers": {
    "accept": "*/*",
    "accept-language": "pt-BR,pt;q=0.9,en-US;q=0.8,en;q=0.7,ar;q=0.6",
    "content-type": "application/x-www-form-urlencoded",
    "Api-Key":"{{token}}"
  },

  "referrerPolicy": "strict-origin-when-cross-origin",
  "method": "GET",
  "mode": "cors",
  "credentials": "omit"
});
   console.log(await res.json()); 
})();

```
## Listagem de jogos por provedor

```javascript

(async()=>{
const res = await fetch("https://bsigaming.online/api/games/PgSoft", {
  "headers": {
    "accept": "*/*",
    "accept-language": "pt-BR,pt;q=0.9,en-US;q=0.8,en;q=0.7,ar;q=0.6",
    "content-type": "application/x-www-form-urlencoded",
    "Api-Key":"{{token}}"
  },

  "referrerPolicy": "strict-origin-when-cross-origin",
  "method": "GET",
  "mode": "cors",
  "credentials": "omit"
});
   console.log(await res.json()); 
})();

```

## Listagem de provedores

```javascript

(async()=>{
const res = await fetch("https://bsigaming.online/api/providers", {
  "headers": {
    "accept": "*/*",
    "accept-language": "pt-BR,pt;q=0.9,en-US;q=0.8,en;q=0.7,ar;q=0.6",
    "content-type": "application/x-www-form-urlencoded",
    "Api-Key":"{{token}}"
  },

  "referrerPolicy": "strict-origin-when-cross-origin",
  "method": "GET",
  "mode": "cors",
  "credentials": "omit"
});
   console.log(await res.json()); 
})();

```
## Game Launch

```javascript

(async()=>{
const res = await fetch("https://bsigaming.online/api/game/launch/{{gameId}", {
  "headers": {
    "accept": "*/*",
    "accept-language": "pt-BR,pt;q=0.9,en-US;q=0.8,en;q=0.7,ar;q=0.6",
    "content-type": "application/x-www-form-urlencoded",
    "Api-Key":"{{token}}"
  },

  "referrerPolicy": "strict-origin-when-cross-origin",
  "body": "&user_email=tgpnet37@gmail.com&user_balance=384",
  "method": "POST",
  "mode": "cors",
  "credentials": "omit"
});
   console.log(await res.json()); 
})();

```
