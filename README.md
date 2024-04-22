money maker# hello-world
Ce référentiel est destiné à pratiquer le GitHub Flow 
i want my token
import { CovalentClient } from "@covalenthq/client-sdk";

const ApiServices = async () => {
    const client = new CovalentClient("cqt_rQj6JybWjRHJFCRvY6bxDC4yJt4f");
    const resp = await client.BalanceService.getTokenBalancesForWalletAddress("eth-mainnet","0x0d4ddea3849c54e16c85cb4354943dc876e05552");
    console.log(resp.data);
}nice
