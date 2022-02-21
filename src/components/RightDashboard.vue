<template>
  <div class="header">
    <p class="text-center text-muted pt-5">Quit</p>
    <p class="text-center text-muted pt-5">Personal</p>
    <p class="text-center pt-4">
      <img
        width="35"
        src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAoHCBYWFRgWFhYYGRgaGhkcGBwYGRoYGBgaGBocGhkYGhgcIS4lHB4rIRgZJjgmKy8xNTU1GiQ7QDs0Py40NTEBDAwMEA8QHxISHjQhISQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDE0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQxNDQ0P//AABEIAPoAyQMBIgACEQEDEQH/xAAbAAABBQEBAAAAAAAAAAAAAAADAQIEBQYHAP/EAEQQAAIBAgMFBQYDBQYEBwAAAAECAAMRBCExBRJBUXEGImGBoTKRscHR8AcTchRCUmKiJIKywuHxFUNzsxYjMzREU5L/xAAZAQADAQEBAAAAAAAAAAAAAAAAAQIDBAX/xAAiEQEBAQEAAgICAwEBAAAAAAAAAQIRITEDEkFRIjJxYRP/2gAMAwEAAhEDEQA/ANMiw6JAUpLSCCoJIWCUQiwB27FAiqY4iAKpikRk89UKLsQBzJsM8hnAPNGvVVRdiFA1JNhKTbfaRKV0Sz1PEgIn8ztfQam3DyvjMV2wqkllsSGJFyGXQgFbKpG7wPMQHXRcTtKmmrKDe3fJQaX1I+AOZEfhcWr3A9pbbwz0OhFwCVOedhoeU4s+3azls1tlfuIONwSbX58b+McO0mJW5Ws4JG6W3mvY52Bz3c88rZ5wDtrVVUEswAGpJAA8zCrUUi4II5gzgv8AxnEAEGtUzvfvkjpY878Yelt+vleoTa3dvlYAm1uIvuj+4OUYdvqgiQ6rTn2we2ZQbtSxXOxUKGVf3SRkpB0tlbhwm5w2MSqgdDcEdDn8eoyyiBMUl6TeEkbPF0XpGMl0fpCbKPcEIEpVjyMoQLEZYyVeMFmU/wAw+MvNzKUuN1X9Q+Mv1XIdI4KiskA9OT2SBdI0qurSkf8AJlpUSA3IBAVYZDGpCWkLEVocSKDC0ngKKI9TGiOjJ53ABJ0E5z2p2wXfd7w3S1hvEC98rrpcDL5zX9oNoimlge+cx/KNCfkJy7GuzvbXO1tGHkT9+EY9o9WqWcXJIuT9+djItUGwHA29T9AvpLcbLewuCDwJGRORFjyNvWBq7PbgpFtPAa28bG+fIyftFfWqw07KepPnf5fEiCFMZnlpyBvb4298sjgHy7vH7t6RlPZTtkFPDh/MDmfKK2Q5m3wrWTNjp8h4ffOBZB/vb1v8JcvsdxcbrZ/W1/vnI9bZLrbL/cxffP7V/wCev0rQ7AG4JH+xHwml7KbV3HVHcqh47zhUN9e6ctSc7i7HLOUGJR11X75coBKlj118JUqLHZ9k7ZDpuP7R3l3x7DsCd3oWAYgfynwltsr2ZyfY+2HFqeQsy2Yn2cxv66grfLnYi3Hqew8Qri6m/PUfGBLpY5ljQI8RpVOPXNf1D4zRIMh0lHjxp1Hxl/THdHSOGGywLrJRWDZY0oVRIHdkyosBuwCnQQkVViESV9ITPB7RjRl4gsEeO3pV4naC0k330uALZkk6AAak2mU2j2jqPcpvKveCFcgSjbr3vmRlxA48M4yC7V7SZ6hVcwbIotnbwHiby42B2WVFV3ALHPMaXlF2Ywn52JBI7qZ6e0xzuZ0l8spl8mvw3+LPPKCNnIBa3oJ79jTTdEmtB2mFdUV2J2YjaqPgfeINNnIgyGstDBVRI0ue1e2FXlI1bZyHVbyyYQdSZ1rPKlxGxkYEbo90ye3ezJCl0WxHLjOggwOJUMLc5Wd3N8FvGdTljkDUSAGHtC28Drfpabzsbj6xQspO8pLNvDeDl7FVJOdiS3G+Y6HM7cwu47W4Nfy8PpE7P7WejXBVyA5AICb1xe2QbTlnO/Ouzryt5+t47TsXaS4imHUWILI63vuuuTC/EaEaZEaaSwKzEdgsURVxNJ2UuXFUFTdW3771jxINgTzE3YlIVeO4dR8Zf0h3R0lDj106iaCiO6OkICERjCGIjGEokVxA7slOIG0CVQpzzUpLKxpElfEB6JgGpmWbCM/LvEGG7XVyoXMDczAPEkEnpkuvM8rzKqwdyQLK1msFyBPeccwPTO/jNj2ywqliC+4WA3eV1H73Iae6/XJYeg67wcEC3HLIGwsPXLlKhVsewVG+89tT7ps66d7pMp2GNktyPzmuqH76THToz+ADaNYTzCIFmWm+TLQdWSAucbUTKRVyoDmRamssXpSJWSZajbOkUGMYwri0CymSrrE9qFsSeOfpymXqVDdSNbC9uel/A2A+M0nbEm453maU7xB0yA56fZ989D4v6x5nzf3rWfhtVP7YuveDfDIdMp2cTkf4dUB+0IzZZtu65tuHI+XqJ1+00YVXY75y/oDujpM/jvnNBQ9kdIGcRGMI+0RoxUdxA2klxA2jSgq08RBqY8NJUaRPAxxjbRBXba2OldCDk1smFgfDvWuPLxnKsVgqtKoabuNy9gb6530vppfKdoUzD9usKWZXRC1siUF2DZWuutrHIxyjnUrsfaxA0uQLcAPoCB5TXss592NxbDEojXAZXFjwa97HxsJ0DF1dxb2uZGp5bZvITcEaVAmex+3Wp97Jh19LcJW0+2O8bbnuN/sTPWWmdxsDEYSswm0lfSSa1fdmdnGsvRnIEhVHEo9s7WdD3LeJPrMrV2riKrEI5t4DL0imPsLv6+G7rVUJtvC8ayTDUKL73eqKDw3rrryuBeajZaOo77Fr6En5SdfHJ6qsfLb7ih7aYTuBxpfPl4GYpXN7H7+s6n2iw4fD1BxCkjqM5zrY2GVm3mIsDoc94gju2GZ1m/xX+P8Ajn+bPdd/bbdksGgajWUvvLkwBBQDQk8dDfqM51BTMb2PwGT3XdFxcZXzByNvAibK01zezrn+TP11xA2gJfYf2R0lBjzL/D+wOkoofEMWIYQAuIK0M8FGlTo0JeREeGDxKEvFBg96e3oDosou0OzqrjeouVN13lvZWzyzsSDwyt46Wl0HhFIMnU8Hm81GD2Zhagx9IvuX7xIUk6KRlpla832IUEWMzVPDhMajkWuWT/8ASmxv1tNPWEnvZ1tzlsZPE4D8zeG6FIBsal90tnZUUcMrFjx4ETHNsctV7+8EAYligXOxK2tnyynV8QAUIt/vKDE4ItkB7pGtci8ZlvnwqOyu+CAwJS9u/wC0ORDfvD4TV4+iLQWy9lBLSdjEGd9JGpfq1ln28OYbepM1Q59waAm1zfMwgwCvRAUDfBOZY7tvALbdtujgdT1GhxmEUte3H4wD7HAzXLp9JGfk+rTXxzShwWxnRLBjvXuxYlk3dN3cbWXWARlUKeGljlY8B4Q1OhbW59JLp0eNvrFrdoziZK9IMjKf3lIPmLTAbDwhVibZK+6TkRfzH3adCZwAzHgCZneyVEMjs2d6hY3HhkfUys2zNZ3l3P8Ajedn03UJ5t8FUfKXAkHZtHdpqOOp8zf5yYpnTiczI4vk19tWq/HjOX+H9kdJQ48y+w3sL0lph5jTHxpiUG4gbQ7wUaKzCNChpHRhzEMpiM/ei70aBHBekYKGiipECR35R5iARu0eHvTWqt9+mVYHlz8tPdLq4K35j4yurIWRkNrMCOl5KwoIpoDwAHuy+UixrNdpHTKMSlxh6srsdiTki6n7MyvhvmdWmHQEayPjUyj8NXRAoJztYnxjcc455R6n8Rm/yUVamDkIFawDbp1gdobXSkQCGZjmFUXNuZJyAkYuKh37W4a55TC58ddGdz0t7CNdRwkXD1st06wpeRw7Zw2sm8ji17qcvKQ9g7NZKQ30IBJYnKxucrHyAlphc2A++Usdo1O6EUW0HhOnGZc+XHv5LNdiywpuohishYW4USWtSdDlqux4l/hvYXpKDatWwl7gT3F6QODxpjo0xKMeDhWgo0s+mz/EwqYS0loYQLJCKmGj/wBlki0crRhD/Zo9aElERhgA/wBlnqibqgQWM2pSojeq1EQfzMB6Sup9pqNZ0RCSH3t1iN0MVF7AHMggN7ofW2HmyVPqv3fKVtBbsXOpNh4c5Lc3FpXYh2VQFFzy87zKyddEt5xMduUq8fi2Vd0keGvxkV9r4hSFOHKji998DyGcJXrBrnfpkg2sUfPLwPWO3sPObL5VpwO+xc94n0yNumVo8Ut0GxjsRXZslLMLaIm4CcrXJueco/8AhdV2Aeo27fNEYgHqR8JnW0zeel4jkgG2n38/SSEfUyPTo7g3eHXykpVztwyv9JnzyVtk4sdlJd18Mz5fYlntBdD4iYPtPtevR3Bh2CsM3JAOWirppqfISDhu3mIsBVRGHMAi/rOrGb9XHvXdOsUUuoilJlNkdt6DgK90PjmvvGk1dGujqGRgwPEG804zQ8fRBEuNnnuL0ldjV7sn7N9hZJxLjTFMSCjWg4RoOUlVIYdGgVEcJIGMaxjQ0i7S2ilFN9z0A1Y8h9YSd9AevikRSzsFUakmc97WfiEVulDu8N4+0eg4CUHantI9RiScuAGg6TEAGo+cv6yf6Xte7KR8ZW36rMUU3e5J3uSfWbfCVFGKwpy3RUUW4WYFLesy+yyEQBRJ1XFGwYHvIysOqm49ROjMkz/1Fvl1XG0yjWOY1B5jOQ927g2+zLdiuJoI6nNlDoeovYyqwzXNjkRkR4jwnFrPK6sa7EliANPdKfH4hRlu3ls6yDicGWMm/ppm2XwqWxVr2W3nf4xtJicytvjJD4Mi5+/hB7h5+vX6TLXG01q+6a63+8sp4MFGfziubX+87RMLSLuq8yPcNYpE29v+MptssuJqo+fdRh0NNTb1MoaylCSunFeE0XbdrY9/+nT+BHylG+fCd2ZyccNvb02i6tmMjyljgNpVaR7jsvQ5e7SU+5Y5SQrRk2WF7Z1gLPuuPHI+8TTbJ7c0d0K6svjqPTOcsRoZHi5A7tg9rUaoulRW8Li/ukycEp1yDcE35jWX+ze1mIpWG/vDk+frrF9f0fa600HMrhO3VEpeoCjcbAsOtwJYf+KcL/8AasPrS6KhhbTO43tNSQdwFzz0X6mZ7G9p6z5BgoP8At6nOE+PV9+B9o1+09sU6INzvN/CPnOf7d2y1Ukk9B8pBxGIZs2N85XYh/v3TSSZ9F79qTa73PWJgaegHWJjxdx5yRgtT4SJ7O+llRaHR+HORqdTwML4zaIdM/DjaW/QaiT3qTZeKPmvuO8PITQbRwZY76e2NRwcDgfHxnK+zG0jh8Sj/uP3H5WY5HyNp19HyvI1mX2Jqy9ijpY0EZ5G9iDqDyM9+1ayRtXZYqd9DuOOP7reDjj11HpM8apDbjruPY5HMMOJRv3h9kCcu83Pv068bmvXsTGYsZ+PX3SH+afqOfXpDMg1sLwLJe8ytjX+VeBJ104D5y57P0L7z+O6PL2vp5SkRGd1pp7Tat/Co1b74kTaYagqIqKLBRYS/ix2/as/l1Mz6z8uTduW/t7+CUx6E/OVBMsu2rXx9Xw/LH9C/WVJM6o5qfrHARgMfAHgxwMYscDGBQZ7fgwY1jAHVK2Rgv2xoKs+UgfmwDWNUz++ECzfT5QDXU8xfT5j6R2/cG3WVamEqHWQ6xkppEqCTVKjHDMdZJwC6nx+Q+sDjxlfxh8B7A6n42+UU9ip6p1jgkGp8TDK3WXEU10ytnOq9jNsfn4dd7207j9Rx8xYzlx6y57DbR/LxO4T3ag/qGY94vHQ60JA2ngEqLuutxw4EHmCMwfESwpxtYSb5E8MLtPCV6GYBq0+YF3X9QHtDxEpau2kIy1+PhadOKTP4lMGtY1KiU1ZSAHIG8zX4KMzu5d6059fDLfDpz89k8pHZnZpp099x/5lSxb+UcE8uPjeXBjqdVHUMjKynQqQR7xEmvJJyMbq6va452vT+3VvEof6B9JULlND25p2xr+KIfiPlM64jBwMUuBmZGetbLU8h8zwhKS8WzPoOkAOhOp46QoMEWigwB5aDdo8wLxhFxL5ayt3pJxz5GC/LiNs61K9ukgEbhz0b0MtG08vlIWLpXvN95/LPNBYwDxaFS/dOoyMc4mK1ZjV7p++Mfgh3F6fGExCXBkTD4tAApO6QLZ5A+cX5CxWGU+MjI/jCfmdJUpUe8BTqFWDrkVYMv8AdNx8Iyo97DnDhcukpLtmxcYKtFHXRlB940kthMR+G+PvTeiTnTa4/S9yPUNNRtTEvuslI9+2bWuE+rSbQqO0e31Rmw9Jr1Ld8j/lhtB+o6+Az5TGV6QC3U+/PzOZ5301aNx+EenVR2Ptjcc53LC5u3M+1JZYlSCw89L5n94cDvHXgJvnM+qbb1X4XaFSg29TcqeIGaNb91l0PLncmdB7P7fXEKAy7lQDvIePip4j1mC2Vhd+uq2yGZHguY+XvM2y7MGRGRHEZGY656VOsh+IKf2pTzpj0ZvrMmxmt7fqwr0t43P5ZF+dmH1mSMlTwSOC+MQTxqqMiYgduxFHeipVVtDee4wMRoGoYYmBq6RhT408PGS9yRMSvfUfzCWO8IoGnJy8oLEcZAw20w11YbrgaH1IPEQz1736Tp7LGSpxj7jh+GjSaj3BkXHqGBkfZmJNihOa+o5zHnni/wAJtRZT1KFyRa/3zl6wvK6snez0PxH2fdJ1FSq1cK6+ySvQ2khHqjUof1a+8Q7JHU0EUgGw6knMDIcCTr1k1Tx98BSklZcTVr2Sxhp4tBey1AUPX2l87i3nOr0aQAynDa7lbOvtIQynxU3HwnZ9iYv8xEbgyhh5i/zka9nFPt3DBkrIB3lAqL1Fzb+m3nMpg6wK3NvPL32sbZX04Gb2tb8xydN2x6WJnPNm4bcVm5+yDlup+7nwyz3hxuDwm/xa8cZ6nlbdjFU13PDcyvrmwNxkL3tebvdnN9lY38uqraKx3GvrY6E+N8zbxnRKNW4sdRMd/wButM+mD/ElLVKB/lceqzEvN3+JY72HP6/8swb6w/AOEa1FTmQLxVEdAESmF0Fp7eznjGD2jADb0FWaOvA1DfKBq+v7Y8AT8hF/NMbXHfYcrD3R24P4h75PTX9fCo+ozGhGRGvGQsQzoc7stteI015yeTa/3wjqqhh5ffwm3WXFU1YMMjeVlZyj7w8+kmYrCgG6mzfHqJAqOdGFj6HpI1rq5OL7AYkOPKDxSZeo8pRYWuUccr/YmhxGYh37Qc5UQMLR1MwKNmR45QitJNMpSUnxkahzkpBw90uFQ6wynQ/w4xu/hwh1psU8vaX0a3lOfV9Jd/h1j9zEvTN7VFBH6k/0Y+6ToRu9qtb879B+BmNxBytxzvz5nLnxYaHhNrj0u9Qc6Z8eDcJgqzZW8BflbUC/K+d9QSBNfjvM1OvaNUW6+HDp9/ThN92dxX5lBGJ7y9x+q6HzFjMETl9fdn4638bnjND2JxVnemf313h+pf8AQ+kz0cD/ABK/+P1qf5Zgqms3/wCJA/8Ab9X+AmAq6mL8B5Gi3jBHAwM4nKDGpjmMErZmBnu0CjZknRQT7ortAYt92mebHd+Z9BC0IAcm/Mm5PWe/Li0xlHSDX35utjPftVsmkRmbwOfEeMY9XmCPX4zXrNH2ilzvDlIQq7w3X8pLqBjoQ3ofcZX4hfIzLV8tIeEHHwt1mhpNdDMtTe7DrNHgHuD0l/HfadItTJh45ff3xhES5jMUl7/fnJGBbeAPv6jURfk0+gskbsGi284j1LSiJWOUj7Mxf5WJpVL5LUW/6Sd1vQmeareRcSlwYqHdmW9TqgnNqotkdf3r65eH8XEjjccpu+zeL/Ow9CqdTTUN+oZN6gzC4v23HDeP+I2F+vuOWkrF8Ur7BY5ePv5AAeVv6fGF2TidytTf+cX/AEnI+hPu53gG0+7Em/8Ar/UOEAx5cch5Zk/A+8iFDVfiMO7QP8z/AOGc9qHObntliN/DYV/4r+/cz9Zhaxzi/AhoaKTBFp4vEo9ngt75xXaCWAPXOA2q/sLyufl9ZLorKvG1N6ox6AeUnXo57IsdeMWOiC3GnnPMl9fCKuh6/Seq/T5zSoiI9EcJFxCZZiTvp9JGxPsiRVRUOm61+Hwl1s18usq8Tp7vjJuz+EMez16S8Sc4LBvuvbg3+Lh7/kIV+H3zkbEewY9eynpePUykZqhj6vs+cEsoiLFfOeiNAOifhtir4Z0P/Lc26OA3xLSirvdmPixPU8/n7+Em/h17WJ/RT/zyup6jqPjDP5Kkc+/TPW5OdzzvlfnY6GRqh+g4efhmf7pJ4Q40HQf4TI9XUeX+Fo6EzaGK3sHRX+Cu6+9d/T+9M3XOZllV/wDRH/Xb/tyrfWK+hA2MYTPPGmSZXOUQNaNrcJ6hpA0pBfXIcufU/KUpa7E8yTLl/ZbofhKWnJ0eRgZ7eiCLEp//2Q=="
      />
    </p>
  </div>
  <div class="paymentText position-relative mt-4 pt-4 px-3">
    <p>Payments</p>
    <button
      class="
        position-absolute
        top-50
        end-0
        translate-middle-y
        btn btn-light
        py-1
        px-3
        mt-2
      "
    >
      Clear
    </button>
  </div>
  <div class="payCards px-3">
    <div class="shadow p-2 mb-2 bg-white rounded">
      <div class="payCard">
        <i class="bi bi-credit-card-2-back-fill"
          ><svg
            xmlns="http://www.w3.org/2000/svg"
            width="16"
            height="16"
            fill="currentColor"
            class="bi bi-credit-card-2-back-fill"
            viewBox="0 0 16 16"
          >
            <path
              d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v5H0V4zm11.5 1a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 .5.5h2a.5.5 0 0 0 .5-.5v-1a.5.5 0 0 0-.5-.5h-2zM0 11v1a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-1H0z"
            /></svg
        ></i>
        <p>Recieved LTC</p>
        <p>+15.00 USD</p>
      </div>
      <div class="pt-3">
        <p class="date">2018-8-3 //11:12:40</p>
      </div>
    </div>

    <div class="shadow p-2 mb-5 bg-white rounded">
      <div class="payCard">
        <i class="bi bi-credit-card-2-back-fill"
          ><svg
            xmlns="http://www.w3.org/2000/svg"
            width="16"
            height="16"
            fill="currentColor"
            class="bi bi-credit-card-2-back-fill"
            viewBox="0 0 16 16"
          >
            <path
              d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v5H0V4zm11.5 1a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 .5.5h2a.5.5 0 0 0 .5-.5v-1a.5.5 0 0 0-.5-.5h-2zM0 11v1a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-1H0z"
            /></svg
        ></i>
        <p>Recieved LTC</p>
        <p>+15.00 USD</p>
      </div>
      <div class="pt-3">
        <p class="date">2018-8-3 //11:12:40</p>
      </div>
    </div>
    <div class="shadow-none p-3 mb-5 rounded transfer">
      <i class="bi bi-pencil-fill"
        ><svg
          xmlns="http://www.w3.org/2000/svg"
          width="16"
          height="16"
          fill="currentColor"
          class="bi bi-pencil-fill"
          viewBox="0 0 16 16"
        >
          <path
            d="M12.854.146a.5.5 0 0 0-.707 0L10.5 1.793 14.207 5.5l1.647-1.646a.5.5 0 0 0 0-.708l-3-3zm.646 6.061L9.793 2.5 3.293 9H3.5a.5.5 0 0 1 .5.5v.5h.5a.5.5 0 0 1 .5.5v.5h.5a.5.5 0 0 1 .5.5v.5h.5a.5.5 0 0 1 .5.5v.207l6.5-6.5zm-7.468 7.468A.5.5 0 0 1 6 13.5V13h-.5a.5.5 0 0 1-.5-.5V12h-.5a.5.5 0 0 1-.5-.5V11h-.5a.5.5 0 0 1-.5-.5V10h-.5a.499.499 0 0 1-.175-.032l-.179.178a.5.5 0 0 0-.11.168l-2 5a.5.5 0 0 0 .65.65l5-2a.5.5 0 0 0 .168-.11l.178-.178z"
          /></svg></i
      >&nbsp;&nbsp;&nbsp;&nbsp; + New Transfer
    </div>
    <div class="paymentText">
      <p>Wallets</p>
    </div>
    <div>
      <table class="table table-borderless">
        <tbody>
          <tr class="d-flex align-items-center">
            <th scope="row">
              <i class="bi bi-currency-bitcoin"
                ><svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="16"
                  height="16"
                  fill="currentColor"
                  class="bi bi-currency-bitcoin"
                  viewBox="0 0 16 16"
                >
                  <path
                    d="M5.5 13v1.25c0 .138.112.25.25.25h1a.25.25 0 0 0 .25-.25V13h.5v1.25c0 .138.112.25.25.25h1a.25.25 0 0 0 .25-.25V13h.084c1.992 0 3.416-1.033 3.416-2.82 0-1.502-1.007-2.323-2.186-2.44v-.088c.97-.242 1.683-.974 1.683-2.19C11.997 3.93 10.847 3 9.092 3H9V1.75a.25.25 0 0 0-.25-.25h-1a.25.25 0 0 0-.25.25V3h-.573V1.75a.25.25 0 0 0-.25-.25H5.75a.25.25 0 0 0-.25.25V3l-1.998.011a.25.25 0 0 0-.25.25v.989c0 .137.11.25.248.25l.755-.005a.75.75 0 0 1 .745.75v5.505a.75.75 0 0 1-.75.75l-.748.011a.25.25 0 0 0-.25.25v1c0 .138.112.25.25.25L5.5 13zm1.427-8.513h1.719c.906 0 1.438.498 1.438 1.312 0 .871-.575 1.362-1.877 1.362h-1.28V4.487zm0 4.051h1.84c1.137 0 1.756.58 1.756 1.524 0 .953-.626 1.45-2.158 1.45H6.927V8.539z"
                  /></svg
              ></i>
            </th>
            <td>BTE <span class="text-muted">Bitcoin</span></td>
            <td></td>
            <td></td>
            <td>37% <span style="color: aqua;">-2.5%</span></td>
          </tr>
           <tr class="d-flex align-items-center">
            <th scope="row">
              <i class="bi bi-currency-bitcoin"
                ><svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="16"
                  height="16"
                  fill="currentColor"
                  class="bi bi-currency-bitcoin"
                  viewBox="0 0 16 16"
                >
                  <path
                    d="M5.5 13v1.25c0 .138.112.25.25.25h1a.25.25 0 0 0 .25-.25V13h.5v1.25c0 .138.112.25.25.25h1a.25.25 0 0 0 .25-.25V13h.084c1.992 0 3.416-1.033 3.416-2.82 0-1.502-1.007-2.323-2.186-2.44v-.088c.97-.242 1.683-.974 1.683-2.19C11.997 3.93 10.847 3 9.092 3H9V1.75a.25.25 0 0 0-.25-.25h-1a.25.25 0 0 0-.25.25V3h-.573V1.75a.25.25 0 0 0-.25-.25H5.75a.25.25 0 0 0-.25.25V3l-1.998.011a.25.25 0 0 0-.25.25v.989c0 .137.11.25.248.25l.755-.005a.75.75 0 0 1 .745.75v5.505a.75.75 0 0 1-.75.75l-.748.011a.25.25 0 0 0-.25.25v1c0 .138.112.25.25.25L5.5 13zm1.427-8.513h1.719c.906 0 1.438.498 1.438 1.312 0 .871-.575 1.362-1.877 1.362h-1.28V4.487zm0 4.051h1.84c1.137 0 1.756.58 1.756 1.524 0 .953-.626 1.45-2.158 1.45H6.927V8.539z"
                  /></svg
              ></i>
            </th>
            <td>BTE <span class="text-muted">Bitcoin</span></td>
            <td></td>
            <td></td>
            <td>37% <span style="color: aqua;">-2.5%</span></td>
          </tr>
            <tr class="d-flex align-items-center">
            <th scope="row">
              <i class="bi bi-currency-bitcoin"
                ><svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="16"
                  height="16"
                  fill="currentColor"
                  class="bi bi-currency-bitcoin"
                  viewBox="0 0 16 16"
                >
                  <path
                    d="M5.5 13v1.25c0 .138.112.25.25.25h1a.25.25 0 0 0 .25-.25V13h.5v1.25c0 .138.112.25.25.25h1a.25.25 0 0 0 .25-.25V13h.084c1.992 0 3.416-1.033 3.416-2.82 0-1.502-1.007-2.323-2.186-2.44v-.088c.97-.242 1.683-.974 1.683-2.19C11.997 3.93 10.847 3 9.092 3H9V1.75a.25.25 0 0 0-.25-.25h-1a.25.25 0 0 0-.25.25V3h-.573V1.75a.25.25 0 0 0-.25-.25H5.75a.25.25 0 0 0-.25.25V3l-1.998.011a.25.25 0 0 0-.25.25v.989c0 .137.11.25.248.25l.755-.005a.75.75 0 0 1 .745.75v5.505a.75.75 0 0 1-.75.75l-.748.011a.25.25 0 0 0-.25.25v1c0 .138.112.25.25.25L5.5 13zm1.427-8.513h1.719c.906 0 1.438.498 1.438 1.312 0 .871-.575 1.362-1.877 1.362h-1.28V4.487zm0 4.051h1.84c1.137 0 1.756.58 1.756 1.524 0 .953-.626 1.45-2.158 1.45H6.927V8.539z"
                  /></svg
              ></i>
            </th>
            <td>BTE <span class="text-muted">Bitcoin</span></td>
            <td></td>
            <td></td>
            <td>37% <span style="color: aqua;">-2.5%</span></td>
          </tr>
            <tr class="d-flex align-items-center">
            <th scope="row">
              <i class="bi bi-currency-bitcoin"
                ><svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="16"
                  height="16"
                  fill="currentColor"
                  class="bi bi-currency-bitcoin"
                  viewBox="0 0 16 16"
                >
                  <path
                    d="M5.5 13v1.25c0 .138.112.25.25.25h1a.25.25 0 0 0 .25-.25V13h.5v1.25c0 .138.112.25.25.25h1a.25.25 0 0 0 .25-.25V13h.084c1.992 0 3.416-1.033 3.416-2.82 0-1.502-1.007-2.323-2.186-2.44v-.088c.97-.242 1.683-.974 1.683-2.19C11.997 3.93 10.847 3 9.092 3H9V1.75a.25.25 0 0 0-.25-.25h-1a.25.25 0 0 0-.25.25V3h-.573V1.75a.25.25 0 0 0-.25-.25H5.75a.25.25 0 0 0-.25.25V3l-1.998.011a.25.25 0 0 0-.25.25v.989c0 .137.11.25.248.25l.755-.005a.75.75 0 0 1 .745.75v5.505a.75.75 0 0 1-.75.75l-.748.011a.25.25 0 0 0-.25.25v1c0 .138.112.25.25.25L5.5 13zm1.427-8.513h1.719c.906 0 1.438.498 1.438 1.312 0 .871-.575 1.362-1.877 1.362h-1.28V4.487zm0 4.051h1.84c1.137 0 1.756.58 1.756 1.524 0 .953-.626 1.45-2.158 1.45H6.927V8.539z"
                  /></svg
              ></i>
            </th>
            <td>BTE <span class="text-muted">Bitcoin</span></td>
            <td></td>
            <td></td>
            <td>37% <span style="color: aqua;">-2.5%</span></td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<script>
export default {
  name: "RightDashboard",
};
</script>

<style scoped>
.header {
  display: flex;
  justify-content: space-around;
}
.header img {
  border-radius: 10%;
}
.paymentText {
  font-size: 28px;
  color: black;
  font-weight: bold;
}
.payCard {
  font-size: 12px;
  display: flex;
  justify-content: space-around;
  align-content: center;
  /* justify-content: space-evenly; */
}
.payCard i {
  background-color: pink;
  padding: 10px;
  border-radius: 50%;
}
.date {
  font-size: 12px;
}
.transfer {
  background-color: #ccb7e5;
}
.transfer i {
  background-color: white;
  padding: 10px;
  border-radius: 10%;
}
th i{
background-color: rgba(255,215,0,.5);
color:rgba(255,215,0,1);
  padding: 10px;
  border-radius: 10%;
}
tr{
    align-items: center;
    align-content: center;
}
span{
  font-size: 11px;
  
}
</style>