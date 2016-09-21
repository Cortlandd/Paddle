# Plan for Paddle game

## Model

TODO: State Shape

```
Gamestate = Play | Pause
```

TODO: Model Shape

```
Model =
  {
		paddle : Paddle
	, blocks : List Block
  }
```

TODO: Blocks Shape

```
Block =
	{ width : Int
	, height : Int
	, visible : Bool  

	}
```

TODO: Ball Shape
```
Ball =
  { radius : number
    -- position
  , x : Int
  , y : Int
  }
```

TODO: Paddle Shape

```
Paddle =
  {
    width : Int
    , height : Int
    , color : Color
    ,
  }
```

TODO: Court Shape

```
Court =
  {
    width : Int
    , height : Int
  }
