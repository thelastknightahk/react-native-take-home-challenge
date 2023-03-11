# Take-home challenge

## Resources

- API: [Pokemon TCG](https://pokemontcg.io)
- Design (Mobile screen only):
  - prototype: <https://www.figma.com/proto/GEbDoXIEkMvK8UrJlcz7Z7/Pokemon-TCG-Marketplace?node-id=1%3A34&scaling=contain&page-id=0%3A1&starting-point-node-id=1%3A34&show-proto-sidebar=1>


## Requirements

- [ ] Able to export apk or ipa (if you are using expo please use bare workflow)
- [ ] Card list:
  - [ ] Implement search/filter (**optional**):
    - [ ] Name
    - [ ] Type
    - [ ] Rarity
    - [ ] Set
  - [ ] Loading/PageSize limit: `12` cards on each api call
  - [ ] Implement `Loadmore` style pagination
- [ ] Use card `price` data from `cardmarket.prices.*`
- [ ] Use card's stock from `set.total`
- [ ] Cart:
  - [ ] Display selected cards as per design
  - [ ] Quantity must be able to increase, decrease & remove. Must respect the stock left limit
  - [ ] Display total number of selected cards
  - [ ] Display total price of all the cards
  - [ ] All cards should be clearable at once from cart

---

You can use any library, plugins & styling solutions.

Make sure to provide a `README.md` on how to run and build your application.

Push the code to a public repo on your account and send us the link.

---

## Bonus

The following are some strategies to leave us with a better impression. But remember, **they're not required**.

- UI should look like as figma for both android & ios
- Using [react native navigation](https://reactnavigation.org/) for pop up modal
- Implementing Authentication flow (api doesn't require authentication but you can include authentication header for simple demonstration)
- Using [react query](https://tanstack.com/query/latest/docs/react/overview)
- Using React hooks
- Using TypeScript
- Meaningful git commit
- Well-structured and organized repository
