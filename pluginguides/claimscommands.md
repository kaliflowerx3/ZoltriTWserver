## Commands
    claim:  
      description: Claim with a specified range around your position.  
      usage: /Claim [range]
    abandonclaim:
      description: Deletes a claim.
      usage: /AbandonClaim
      aliases: [unclaim, declaim, removeclaim, disclaim]
    abandontoplevelclaim:
      description: Deletes a claim and all its subdivisions.
      usage: /AbandonTopLevelClaim
    abandonallclaims:
      description: Deletes ALL your claims.
      usage: /AbandonAllClaims
    trust:
      description: Grants a player full access to your claim(s).
      usage: /Trust <player>  Graants a player permission to build.  See also /UnTrust, /ContainerTrust, /AccessTrust, and /PermissionTrust.
      aliases: tr
    untrust:
      description: Revokes a player's access to your claim(s).
      usage: /UnTrust <player>
      aliases: ut
    containertrust:
      description: Grants a player access to your containers.
      usage: /ContainerTrust <player>.  Grants a player access to your inventory, bed, and buttons/levers.
      aliases: ct
    accesstrust:
      description: Grants a player access to levers and doors in your claim(s) and use of your bed.
      usage: /AccessTrust <player>.  Grants a player access to your bed, buttons, and levers.
      aliases: at
    entrytrust:
      description: Grants a player entry to your claim(s).
      usage: /EntryTrust <player>.  Grants a player access your claim.
      aliases: et
    permissiontrust:
      description: Grants a player permission to grant his level of permission to others.
      usage: /PermissionTrust <player>.  Permits a player to share his permission level with others.
      aliases: pt
    subdivideclaims:
      description: Switches the shovel tool to subdivision mode, used to subdivide your claims.
      usage: /SubdivideClaims
      aliases: [sdc, subdivideclaim]
    basicclaims:
      description: Switches the shovel tool back to basic claims mode.
      usage: /BasicClaims
      aliases: bc
    trapped:
      description: Ejects you to nearby unclaimed land.  Has a substantial cooldown period.
      usage: /Trapped
    trustlist:
      description: Lists permissions for the claim you're standing in or the specified claim ID.
      usage: /TrustList <ClaimID>
      permission: griefprevention.claims
    claimslist:
      description: Lists information about a player's claim blocks and claims.
      usage: /ClaimsList or /ClaimsList <player>
      aliases: [claimlist, listclaims]
    claimexplosions:
      description: Toggles whether explosives may be used in a specific land claim.
      usage: /ClaimExplosions
    claimarea:
      description: Claims an area at specified world, coordinate and range
      usage: /ClaimArea [worldname] [x] [z] [range]
      aliases: [carea]
    autotrust:
      description: Auto trusts all players and fake players that places or breaks a block in 10 seconds in the claim you are standing on
      usage: /autotrust (while standing in your claim)
