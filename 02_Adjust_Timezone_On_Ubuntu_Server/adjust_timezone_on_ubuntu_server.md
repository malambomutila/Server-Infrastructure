# How To Adjust The Timezone On An Ubuntu Server


## Step 1: Check Current Time and Timezone

```bash
timedatectl status
```

## Step 2: List Available Timezones

```bash
timedatectl list-timezones
```

## Step 3: Set The New Timezone

```bash
sudo timedatectl set-timezone Africa/Lusaka
```

## Step 4: Verify The Channge

```bash
timedatectl status
```

