# Myrino
### Myrino is an api-based library for Rubino messengers


## Examples

```python
from myrino import Client
from asyncio import run

client = Client('YOUR-AUTH')
async def main():
    results = await client.follow('followee_id')
    print(results)


run(main())
```

# Install
```bash
pip install myrino -U
```

### contact with me
[Rubika](https://rubika.ir/slash_dev)
[Telegram](https://t.me/activate_sh)
