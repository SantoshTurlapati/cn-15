# Experiment 15: Operating System Detection Using Nmap

## Aim
Use Nmap OS detection and service/version detection on an authorized lab host.

## Requirements
- Computer with the relevant tool/simulator installed
- Authorized local lab target or simulator environment
- Folder to save output and screenshots

## Procedure
1. Install Nmap from the official Nmap website.
2. Open a terminal or command prompt.
3. Choose a target device that you own or have explicit permission to scan.
4. Run OS detection with service/version detection. OS detection may require administrator/root privileges and can be inconclusive.
5. Read the open-port, service/version, OS-guess, and network-distance information in the output.
6. Capture the actual terminal output and include it in the report.

## Commands / examples

### OS and service/version detection
```text
nmap -O -sV <authorized-target-IP>
```

### Linux command if elevated permissions are needed
```text
sudo nmap -O -sV <authorized-target-IP>
```

## Observation table

| No. | Test / configuration | Observed result | Evidence file |
|---:|---|---|---|
| 1 | Initial run | Fill in after your run | `evidence/` |
| 2 | Changed configuration / second test | Fill in after your run | `evidence/` |

## Result
Write the result only after completing the practical and checking the actual output.

## Conclusion
This experiment helps study the relevant network tool/simulator and interpret its results.

## Important notes
The supplied practical shows example output with Windows OS guesses. Those are sample results from the source document, not results from your own computer.

## Evidence checklist
- [ ] Screenshot of setup or topology
- [ ] Screenshot of command/configuration
- [ ] Screenshot of actual output/results
- [ ] Record the date, environment, and parameters changed
