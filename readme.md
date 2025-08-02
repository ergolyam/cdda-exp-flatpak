# cdda-exp-flatpak
My flatpak repository for experimental builds of Cataclysm: Dark Days Ahead.

## Using the Flathub repository

- Add repository:
    ```bash
    flatpak remote-add --user cdda-exp https://ergolyam.github.io/cdda-exp-flatpak/ergolyam.flatpakrepo
    ```

- Install package:
    ```bash
    flatpak install --user cdda-exp org.cataclysmdda.CataclysmDDA.experimental
    ```

- To prevent the package from updating automatically, fix this:
    ```bash
    flatpak mask --user org.cataclysmdda.CataclysmDDA.experimental
    ```
    - You can update a fixed package as follows:
        ```bash
        flatpak update --user org.cataclysmdda.CataclysmDDA.experimental
        ```
