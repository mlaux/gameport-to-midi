# Game port to MIDI adapter

This adapter allows the connection of MIDI devices to the 'game port' or joystick port found on old sound cards. It's similar to the reference circuit given in the MIDI specification, but obsolete parts have been replaced with modern equivalents.

KiCad schematic and layout files are provided, as well as three custom footprints (the DIN-5 MIDI connector, the DA-15 game port connector, and the MIDI logo).

<table>
    <tr>
        <td>
            <img src='https://raw.githubusercontent.com/mlaux/gameport-to-midi/main/images/pcbfront.png'>
        </td>
        <td>
            <img src='https://raw.githubusercontent.com/mlaux/gameport-to-midi/main/images/pcbback.png'>
        </td>
    </tr>
</table>

## Bill of Materials

<table>
    <thead>
        <tr>
            <th>Reference</th>
            <th>Value</th>
            <th>Mouser P/N</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>J1</td>
            <td>DA-15 PCB mount connector, pin</td>
            <td>636-182-015-113R531</td>
        </tr>
        <tr>
            <td>J2-J3</td>
            <td>DIN-5 180° socket</td>
            <td>502-57PC5F</td>
        </tr>
        <tr>
            <td>U1</td>
            <td>74HCT04 hex inverter</td>
            <td>595-SN74HCT04N</td>
        </tr>
        <tr>
            <td>U2</td>
            <td>H11L1M optoisolator</td>
            <td>512-H11L1M</td>
        </tr>
        <tr>
            <td>R1-R4</td>
            <td>270 ohm, 1/4 watt</td>
            <td></td>
        </tr>
        <tr>
            <td>C1</td>
            <td>0.1 μF</td>
            <td></td>
        </tr>
        <tr>
            <td>D1</td>
            <td>Small signal, 1N4148</td>
            <td></td>
        </tr>
    </tbody>
</table>

I also recommend IC sockets because they're cheap and look nice.

## License

GNU General Public License v3
