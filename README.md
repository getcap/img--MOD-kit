# img--MOD-kit

```
@for /f "delims=" %f in ('dir /s /b /a-d *.res') do @del /f /q "%f"
@for /f "delims=" %f in ('dir /s /b /a-d *.bat') do @del /f /q "%f"
@for /f "delims=" %f in ('dir /s /b /a-d *.SPR') do @del /f /q "%f"
@for /f "delims=" %f in ('dir /s /b /a-d *.txt') do @del /f /q "%f"
```