-- Table: client.ID

-- DROP TABLE client."ID";

CREATE TABLE client."ID"
(
    "INS" bigint NOT NULL,
    "InsuranceName" character(100) COLLATE pg_catalog."default" NOT NULL,
    "AuthorizationDate" Date,
    "VerificationDate" character(100) COLLATE pg_catalog."default",
    "Phone" bigint,
    CONSTRAINT "client.ID" PRIMARY KEY ("Insurance")
)

TABLESPACE pg_default;

ALTER TABLE client."ID"
    OWNER to postgres;

-- Table: client.ID

-- DROP TABLE client."ID";

CREATE TABLE client."ID"
(
    "clientID" bigint NOT NULL,
    "LastName" character(100) COLLATE pg_catalog."default",
    "FirstName" character(100) COLLATE pg_catalog."default",
    "Phone" bigint,
    "InvoiceDate" date,
    "Verification" character(100) COLLATE pg_catalog."default",
    "Price" money,
    "Alloted" money,
    "Total" money,
    CONSTRAINT "Client_pkey" PRIMARY KEY ("client.ID")
)

TABLESPACE pg_default;

ALTER TABLE client."ID"
    OWNER to postgres;
