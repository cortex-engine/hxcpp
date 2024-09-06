
To activate the tracy integration, compile with:

```
-D HXCPP_TRACY
-D HXCPP_STACK_TRACE
```

and use the following call in your mainloop:

```
untyped __cpp__('FrameMark');

```

then start Tracy listening on localhost and start your hxcpp-made exe. 