# Interest Rate Model

## APY Function

Borrow APY

= Base + min\(Multiplier \* __UtilizationRate, Multiplier \* Kink\) + max\(JumpMultiplier \* UtilizationRate - Kink, 0\)



Supply APY

= annualized\[de–annualized\(Borrow APY\) - Reserve Factor\]

## Stable + Major

![](https://i.imgur.com/5aoSePr.png)

<table>
  <thead>
    <tr>
      <th style="text-align:left">Parameter</th>
      <th style="text-align:left">Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Category</td>
      <td style="text-align:left">Major &amp; Stable</td>
    </tr>
    <tr>
      <td style="text-align:left">Tokens</td>
      <td style="text-align:left">
        <p>USDT, USDC, BUSD, yCRV, yUSD, ETH, renBTC, FTT, yETH, BBTC, HBTC, HUSD,
          DAI, tBTC, WBTC, sUSD, FRAX, BAC</p>
        <p>
          <br />UNI-V2-WBTC-ETH, UNI-V2-ETH-USDT, UNI-V2-DAI-ETH, UNI-V2-USDC-ETH</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Base</td>
      <td style="text-align:left">2%</td>
    </tr>
    <tr>
      <td style="text-align:left">Multiplier</td>
      <td style="text-align:left">25%</td>
    </tr>
    <tr>
      <td style="text-align:left">JumpMultiplier</td>
      <td style="text-align:left">500%</td>
    </tr>
    <tr>
      <td style="text-align:left">Kink</td>
      <td style="text-align:left">80%</td>
    </tr>
    <tr>
      <td style="text-align:left">Contract Address</td>
      <td style="text-align:left"><a href="https://etherscan.io/address/0x014872728e7D8b1c6781f96ecFbd262Ea4D2e1A6">0x014872728e7D8b1c6781f96ecFbd262Ea4D2e1A6</a>
      </td>
    </tr>
  </tbody>
</table>

## Governance + Seed

![](https://i.imgur.com/Fg4vOj7.png)

| Parameter | Value |
| :--- | :--- |
| Category | Governance & Seeds |
| Tokens | COMP, BAL, YFI, LINK, CREAM, AAVE, CRV, MTA, SRM, UNI, SUSHI, wNXM, SWAG, CEL, DPI, BOND, KP3R, HFIL, CRETH2, HEGIC, ESD, COVER, 1INCH, OMG, xSUSHI, SNX, PICKLE, AKRO, bBADGER, OGN, AMP, ALPHA |
| Base | 2% |
| Multiplier | 35% |
| JumpMultiplier | 750% |
| Kink | 80% |
| Contract Address | [0xd34137FC9F6754bcDFCe907d06F4D10E897B3eB5](https://etherscan.io/address/0xd34137FC9F6754bcDFCe907d06F4D10E897B3eB5) |

## SushiSwap Liquidity Provider token \(SLP\)

![](../.gitbook/assets/jie-tu-20210226-12.32.39.png)

<table>
  <thead>
    <tr>
      <th style="text-align:left">Parameter</th>
      <th style="text-align:left">Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Category</td>
      <td style="text-align:left">SLP</td>
    </tr>
    <tr>
      <td style="text-align:left">Tokens</td>
      <td style="text-align:left">
        <p>SLP-WBTC-ETH,</p>
        <p>SLP-DAI-ETH,</p>
        <p>SLP-USDC-ETH,</p>
        <p>SLP-ETH-USDT,</p>
        <p>SLP-SUSHI-ETH,</p>
        <p>SLP-YFI-ETH</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Base</td>
      <td style="text-align:left">10%</td>
    </tr>
    <tr>
      <td style="text-align:left">Multiplier</td>
      <td style="text-align:left">55%</td>
    </tr>
    <tr>
      <td style="text-align:left">JumpMultiplier</td>
      <td style="text-align:left">180%</td>
    </tr>
    <tr>
      <td style="text-align:left">Kink</td>
      <td style="text-align:left">50%</td>
    </tr>
    <tr>
      <td style="text-align:left">Contract Address</td>
      <td style="text-align:left"><a href="https://etherscan.io/address/0x66FB6cf0Af2Cb8f967F2439Ea855387cB431Fed8">0x66FB6cf0Af2Cb8f967F2439Ea855387cB431Fed8</a>
      </td>
    </tr>
  </tbody>
</table>

